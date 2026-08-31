<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=200&section=header&text=Ki-Hun%20Kim&fontSize=52&fontColor=ffffff&fontAlignY=34&animation=fadeIn&desc=Reinforcement%20Learning%20%7C%20Combinatorial%20Optimization&descSize=18&descAlign=50&descAlignY=54" width="100%" alt="header"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=700&lines=Constrained%20Deep%20RL%20for%20Online%203D%20Bin%20Packing;Safe%20RL%20%C2%B7%20Vehicle%20Routing%20%C2%B7%20Operations%20Research;Turning%20NP-hard%20logistics%20into%20learnable%20policies" alt="typing"/>

<br/>

<a href="mailto:kimkihun811@inha.edu"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/></a>
<!-- TODO: href="#" 를 공개 포트폴리오 링크로 교체하세요. 없으면 이 줄을 삭제하면 됩니다 -->
<a href="#"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=notion&logoColor=white" alt="portfolio"/></a>

<img src="https://img.shields.io/github/followers/kkihoo?style=flat-square&logo=github&label=Followers&color=58A6FF" alt="followers"/>
<img src="https://komarev.com/ghpvc/?username=kkihoo&style=flat-square&color=58A6FF&label=Profile+Views" alt="views"/>

</div>

---

## 🧭 About Me

```yaml
name:        Ki-Hun Kim (김기훈)
affiliation: Inha University          # TODO: 학과 / 연구실명 추가
location:    Seoul, Republic of Korea
field:       Deep Reinforcement Learning x Operations Research
focus:       Constrained / Safe RL for NP-hard logistics problems
motto:       "Optimality is a constraint, not a hope."
```

제약이 존재하는 실제 물류 최적화 문제를 **심층강화학습(DRL)** 으로 해결하는 연구를 수행합니다.
단순히 보상을 최대화하는 정책이 아니라, **실행 가능성(feasibility)과 안전 제약을 보장하면서**
근최적해를 산출하는 정책 구조를 설계하는 데 관심이 있습니다.

- 🎯 **Online 3D Bin Packing** — 우선순위(priority)를 고려한 제약 강화학습 정책
- 🚚 **3L-CVRP** — 적재 제약을 갖는 차량경로문제, branch-and-cut / branch-and-price 하이브리드
- 🛡️ **Safe RL** — Lagrangian relaxation, PPO-Lagrangian, CMDP 기반 제약 처리
- 🤝 **MARL** — 다중 에이전트 협력 하 자원 배분 (2026 기초연구실 과제)

---

## 🔬 Research Focus

<table>
<tr>
<td width="50%" valign="top">

### 🧩 Constrained DRL

제약 마르코프 결정과정(CMDP) 하에서 정책을 학습합니다.
소프트 제약(Lagrangian)과 하드 제약(action masking)을 결합해
실행 가능성을 보장하는 구조를 다룹니다.

`CMDP` `PPO-Lagrangian` `Action Masking` `Primal-Dual`

</td>
<td width="50%" valign="top">

### 📦 Combinatorial Optimization

3D-BPP, CVRP, 3L-CVRP 등 NP-hard 문제를
학습 기반 휴리스틱과 정확해 기법(exact method)의
하이브리드로 접근합니다.

`3D-BPP` `3L-CVRP` `Branch-and-Cut` `Column Generation`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Empirical Validation

합성 데이터에 머무르지 않고 실제 물류 데이터
(Amazon Last Mile Challenge, Olist)를 사용해
정책의 일반화 성능을 검증합니다.

`Amazon Last Mile` `Olist` `Real-world Benchmark`

</td>
<td width="50%" valign="top">

### 🤖 Deep Learning Systems

비전·자세추정 모델 파인튜닝부터
대규모 RL 학습 파이프라인 구축까지
실험 환경을 end-to-end로 구성합니다.

`PyTorch` `YOLO` `ViTPose` `Vectorized Envs`

</td>
</tr>
</table>

---

## 📄 Selected Work

> ### Constrained Deep Reinforcement Learning for the Priority-Aware Online 3D Bin Packing Problem
>
> 우선순위 제약을 만족하면서 공간 활용률을 극대화하는 제약 DRL 프레임워크.
> PPO-Lagrangian 계열 baseline 대비 제약 위반율과 활용률 사이의 trade-off를 정량적으로 분석.
>
> <sub>`Working paper` — TODO: 투고/게재 상태와 arXiv·DOI 링크 추가</sub>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Deep Learning / RL**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium-0081A5?style=flat-square&logo=openaigym&logoColor=white)
![Ray RLlib](https://img.shields.io/badge/Ray%20RLlib-028CF0?style=flat-square&logo=ray&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

**Optimization / OR**

![Gurobi](https://img.shields.io/badge/Gurobi-EE3524?style=flat-square&logo=gurobi&logoColor=white)
![NVIDIA cuOpt](https://img.shields.io/badge/NVIDIA%20cuOpt-76B900?style=flat-square&logo=nvidia&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Overleaf](https://img.shields.io/badge/Overleaf-47A141?style=flat-square&logo=overleaf&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)

</div>

---

## 📌 Featured Repositories

<table>
<tr>
<td width="50%" valign="top">

#### 🚚 [3L-CVRP Exact Loading Oracle](https://github.com/kkihoo/3L-CVRP_B-C_GOPT-Exact-Loading-Oracle)

3D 적재 제약을 갖는 차량경로문제용 하이브리드 최적화 및 fallback 실행가능성 oracle.
branch-and-cut에서 검증되었고 branch-and-price에서 재사용 가능.

![lang](https://img.shields.io/github/languages/top/kkihoo/3L-CVRP_B-C_GOPT-Exact-Loading-Oracle?style=flat-square&color=3776AB)
![commit](https://img.shields.io/github/last-commit/kkihoo/3L-CVRP_B-C_GOPT-Exact-Loading-Oracle?style=flat-square&color=58A6FF)

</td>
<td width="50%" valign="top">

#### 🏆 [Optimization Grand Challenge 2026](https://github.com/kkihoo/OGC-2026---Optimization-Grand-Challenge)

대규모 조합최적화 경진대회 참가 코드베이스.
휴리스틱·메타휴리스틱·수리계획 접근의 통합 실험 환경.

![lang](https://img.shields.io/github/languages/top/kkihoo/OGC-2026---Optimization-Grand-Challenge?style=flat-square&color=3776AB)
![commit](https://img.shields.io/github/last-commit/kkihoo/OGC-2026---Optimization-Grand-Challenge?style=flat-square&color=58A6FF)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🤸 [YOLO + ViTPose Fine-Tuning](https://github.com/kkihoo/YOLO-ViTPose-Fine-Tuning-)

객체 검출(YOLO)과 자세추정(ViTPose)의
2-stage 파이프라인 파인튜닝 실험.

![lang](https://img.shields.io/github/languages/top/kkihoo/YOLO-ViTPose-Fine-Tuning-?style=flat-square&color=3776AB)
![size](https://img.shields.io/github/repo-size/kkihoo/YOLO-ViTPose-Fine-Tuning-?style=flat-square&color=58A6FF)

</td>
<td width="50%" valign="top">

#### 🌱 [codetree TILs](https://github.com/kkihoo/codetree-TILs)

알고리즘 문제 해결 기록.
꾸준함이 곧 실력이라는 전제 하의 일일 커밋.

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
