<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=200&section=header&text=Ki-Hun%20Kim&fontSize=52&fontColor=ffffff&fontAlignY=34&animation=fadeIn&desc=Reinforcement%20Learning%20%7C%20Combinatorial%20Optimization&descSize=18&descAlign=50&descAlignY=54" width="100%" alt="header"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=700&lines=Constrained%20Deep%20RL%20for%20Online%203D%20Bin%20Packing;Safe%20RL%20%C2%B7%20Vehicle%20Routing%20%C2%B7%20Operations%20Research;Turning%20NP-hard%20logistics%20into%20learnable%20policies" alt="typing"/>

<br/>

<a href="mailto:kimkihun811@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/></a>

<img src="https://img.shields.io/github/followers/kkihoo?style=flat-square&logo=github&label=Followers&color=58A6FF" alt="followers"/>
<img src="https://komarev.com/ghpvc/?username=kkihoo&style=flat-square&color=58A6FF&label=Profile+Views" alt="views"/>

</div>

---

## 🧭 About Me

```yaml
name:        Ki-Hun Kim (김기훈)
affiliation: Inha University
location:    Seoul, Republic of Korea
field:       Deep Reinforcement Learning x Operations Research
focus:       Constrained / Safe RL for NP-hard logistics problems
motto:       "Optimality is a constraint, not a hope."
```

I work on real-world logistics optimization problems under constraints, using **deep reinforcement
learning (DRL)**. My interest is not in a policy that simply maximizes reward, but in policy
architectures that **guarantee feasibility and safety constraints** while producing near-optimal solutions.

- 🎯 **Online 3D Bin Packing** — constrained RL policies that account for item priority
- 🚚 **3L-CVRP** — vehicle routing with loading constraints; branch-and-cut / branch-and-price hybrids
- 🛡️ **Safe RL** — Lagrangian relaxation, PPO-Lagrangian, CMDP-based constraint handling
- 🤝 **MARL** — cooperative multi-agent resource allocation (2026 national basic research lab grant)

---

## 🔬 Research Focus

<table>
<tr>
<td width="50%" valign="top">

### 🧩 Constrained DRL

Learning policies under a Constrained Markov Decision
Process (CMDP). Combining soft constraints (Lagrangian)
with hard constraints (action masking) into architectures
that guarantee feasibility.

`CMDP` `PPO-Lagrangian` `Action Masking` `Primal-Dual`

</td>
<td width="50%" valign="top">

### 📦 Combinatorial Optimization

Approaching NP-hard problems — 3D-BPP, CVRP, 3L-CVRP —
as hybrids of learning-based heuristics and
exact methods.

`3D-BPP` `3L-CVRP` `Branch-and-Cut` `Column Generation`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Empirical Validation

Validating how well policies generalize on real logistics
data (Amazon Last Mile Challenge, Olist),
not on synthetic instances alone.

`Amazon Last Mile` `Olist` `Real-world Benchmark`

</td>
<td width="50%" valign="top">

### 🤖 Deep Learning Systems

Building experiment environments end-to-end, from
fine-tuning vision and pose-estimation models to
large-scale RL training pipelines.

`PyTorch` `YOLO` `ViTPose` `Vectorized Envs`

</td>
</tr>
</table>

---

## 📄 Selected Work

> ### Constrained Deep Reinforcement Learning for the Priority-Aware Online 3D Bin Packing Problem
>
> A constrained DRL framework that maximizes space utilization while satisfying priority constraints.
> Quantifies the trade-off between constraint violation and utilization against PPO-Lagrangian baselines.
>
> <sub>`Working paper`</sub>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Deep Learning / RL**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium-0081A5?style=flat-square&logo=openaigym&logoColor=white)

**Optimization / OR**

![Gurobi](https://img.shields.io/badge/Gurobi-EE3524?style=flat-square&logo=gurobi&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Overleaf](https://img.shields.io/badge/Overleaf-47A141?style=flat-square&logo=overleaf&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)

</div>

---

## 📌 Featured Repositories

<table>
<tr>
<td width="50%" valign="top">

#### 🚚 [3L-CVRP Exact Loading Oracle](https://github.com/kkihoo/3L-CVRP_B-C_GOPT-Exact-Loading-Oracle)

Hybrid optimization and fallback feasibility oracle for vehicle routing under 3D loading constraints.
Validated in branch-and-cut, reusable in branch-and-price.

![lang](https://img.shields.io/github/languages/top/kkihoo/3L-CVRP_B-C_GOPT-Exact-Loading-Oracle?style=flat-square&color=3776AB)
![commit](https://img.shields.io/github/last-commit/kkihoo/3L-CVRP_B-C_GOPT-Exact-Loading-Oracle?style=flat-square&color=58A6FF)

</td>
<td width="50%" valign="top">

#### 🏆 [Optimization Grand Challenge 2026](https://github.com/kkihoo/OGC-2026---Optimization-Grand-Challenge)

Codebase for a large-scale combinatorial optimization competition.
A unified harness for heuristic, metaheuristic, and mathematical programming approaches.

![lang](https://img.shields.io/github/languages/top/kkihoo/OGC-2026---Optimization-Grand-Challenge?style=flat-square&color=3776AB)
![commit](https://img.shields.io/github/last-commit/kkihoo/OGC-2026---Optimization-Grand-Challenge?style=flat-square&color=58A6FF)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🤸 [YOLO + ViTPose Fine-Tuning](https://github.com/kkihoo/YOLO-ViTPose-Fine-Tuning-)

Fine-tuning experiments on a two-stage pipeline of
object detection (YOLO) and pose estimation (ViTPose).

![lang](https://img.shields.io/github/languages/top/kkihoo/YOLO-ViTPose-Fine-Tuning-?style=flat-square&color=3776AB)
![size](https://img.shields.io/github/repo-size/kkihoo/YOLO-ViTPose-Fine-Tuning-?style=flat-square&color=58A6FF)

</td>
<td width="50%" valign="top">

#### 🌱 [codetree TILs](https://github.com/kkihoo/codetree-TILs)

A log of algorithm problem solving.
Daily commits, on the premise that consistency is skill.

![lang](https://img.shields.io/github/languages/top/kkihoo/codetree-TILs?style=flat-square&color=3776AB)
![activity](https://img.shields.io/github/commit-activity/y/kkihoo/codetree-TILs?style=flat-square&color=58A6FF)

</td>
</tr>
</table>

---

## 📈 Contribution Streak

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=kkihoo&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D"/>
  <img src="https://streak-stats.demolab.com/?user=kkihoo&theme=default&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="streak stats"/>
</picture>

</div>

<!--
  ┌─ 통계 카드 추가 안내 ────────────────────────────────────────────────────┐
  │ github-readme-stats / github-profile-trophy 의 공개 인스턴스는           │
  │ 현재 무료 쿼터 초과로 죽어 있습니다 (각각 HTTP 503 / 402).               │
  │ → 그대로 붙이면 깨진 이미지가 보이므로 여기서는 제외했습니다.            │
  │                                                                          │
  │ 쓰고 싶다면 본인 Vercel 계정으로 직접 배포하세요 (약 5분):               │
  │   1. https://github.com/anuraghazra/github-readme-stats 를 fork          │
  │   2. Vercel 에 import 후 환경변수 PAT_1 = (GitHub personal access token) │
  │   3. 배포된 도메인으로 아래 URL 의 호스트를 교체하고 주석을 해제         │
  └──────────────────────────────────────────────────────────────────────────┘

<div align="center">
<img src="https://YOUR-APP.vercel.app/api?username=kkihoo&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" height="165" alt="stats"/>
<img src="https://YOUR-APP.vercel.app/api/top-langs/?username=kkihoo&layout=compact&theme=github_dark&hide_border=true&langs_count=8" height="165" alt="top langs"/>
</div>
-->

---

<div align="center">

<sub><i>"The best policy is not the one with the highest reward,<br/>but the one that never violates a constraint it promised to respect."</i></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=120&section=footer" width="100%" alt="footer"/>

</div>
