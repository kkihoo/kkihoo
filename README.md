# Ki-Hun Kim (김기훈)

**Inha University** · Deep Reinforcement Learning × Operations Research
kimkihun811@gmail.com

I work on NP-hard logistics problems with deep reinforcement learning. My interest is in policy architecture — not a policy that maximizes reward, but one that guarantees feasibility and safety constraints while still producing near-optimal solutions.

## Research

- **Constrained and safe RL** — CMDP formulations, Lagrangian relaxation, PPO-Lagrangian, action masking for hard feasibility
- **Online 3D bin packing** — priority-aware loading, where the delivery order constrains what can be placed when
- **3L-CVRP** — vehicle routing under 3D loading constraints; branch-and-cut and branch-and-price hybrids
- **Multi-agent RL** — cooperative resource allocation, under a 2026 national basic research lab grant

I test on real logistics data — Amazon Last Mile Challenge, Olist — rather than synthetic instances alone.

## Selected work

**Constrained Deep Reinforcement Learning for the Priority-Aware Online 3D Bin Packing Problem** · working paper
A constrained DRL framework for priority-aware loading, evaluated on real Amazon last-mile delivery routes. Space utilization is traded against priority violations; the framework makes that trade explicit rather than tuning it away.

## Repositories

- **[3L-CVRP Exact Loading Oracle](https://github.com/kkihoo/3L-CVRP_B-C_GOPT-Exact-Loading-Oracle)** — A loading-feasibility oracle for vehicle routing under 3D packing constraints. A GOPT heuristic decides first; on failure it falls back to an exact method. Validated inside branch-and-cut, reused as-is in branch-and-price. (MIT)
- **[OGC 2026](https://github.com/kkihoo/OGC-2026---Optimization-Grand-Challenge)** — Optimization Grand Challenge entry. Heuristic, metaheuristic, and mathematical programming approaches compared in one harness.
- **[YOLO + ViTPose Fine-Tuning](https://github.com/kkihoo/YOLO-ViTPose-Fine-Tuning-)** — Two-stage detection and pose-estimation pipeline.
- **[codetree-TILs](https://github.com/kkihoo/codetree-TILs)** — Daily algorithm commits.

## Tools

PyTorch · Gymnasium · Ray RLlib · Gurobi · NVIDIA cuOpt · LaTeX
