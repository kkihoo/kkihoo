# Ki-Hun Kim (김기훈)

**Inha University** · Constrained RL × Combinatorial Optimization
kimkihun811@gmail.com

I work on NP-hard logistics problems with deep reinforcement learning. My interest is in policy architecture — not a policy that maximizes reward, but one that guarantees feasibility and safety constraints while still producing near-optimal solutions.

---

## Priority-Aware Online 3D Bin Packing

Boxes arrive in a stream and have to be loaded as they come, while the delivery order is already fixed. A box unloaded later must not block one unloaded earlier. Filling the space and respecting the order pull in opposite directions.

I formulate this as a CMDP and combine a Lagrangian soft constraint with action masking. Results on 385 real delivery routes from the Amazon Last Mile Challenge (hold-out test):

|                                            | Unconstrained baseline (λ=0) | Proposed (τ=0.2) |
| ------------------------------------------ | ---------------------------: | ---------------: |
| Space utilization                          |                        70.9% |        **69.9%** |
| Priority violations (per 100 boxes placed) |                        108.8 |          **9.6** |
| Routes exceeding τ=0.2                     |                        96.9% |         **4.4%** |
| Route completion rate                      |                        99.5% |            86.5% |

One percentage point of utilization buys a 91% reduction in violations. The cost is completion — more routes fail to finish under the constraint. Where to cut that trade-off is still open.

> **Constrained Deep Reinforcement Learning for the Priority-Aware Online 3D Bin Packing Problem** — working paper

---

## Other work

- **[3L-CVRP Exact Loading Oracle](https://github.com/kkihoo/3L-CVRP_B-C_GOPT-Exact-Loading-Oracle)** — A loading-feasibility oracle for vehicle routing under 3D packing constraints. A GOPT heuristic decides first; on failure it falls back to an exact method. Validated inside branch-and-cut, reused as-is in branch-and-price. (MIT)
- **[OGC 2026](https://github.com/kkihoo/OGC-2026---Optimization-Grand-Challenge)** — Optimization Grand Challenge entry. Heuristic, metaheuristic, and mathematical programming approaches compared in one harness.
- **[codetree-TILs](https://github.com/kkihoo/codetree-TILs)** — Daily algorithm commits.

Multi-agent resource allocation (MARL) is ongoing under a 2026 national basic research lab grant.

---

<sub>PyTorch · Gymnasium · Ray RLlib · Gurobi · NVIDIA cuOpt · LaTeX</sub>
