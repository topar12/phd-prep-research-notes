# phd-prep-research-notes

박사 진학(미국 박사 어드미션) 준비 과정에서 작성한 **연구 주제 탐색 노트** 모음.
Personal research-strategy briefs written while preparing for U.S. PhD applications.

---

## 📄 Contents

### `index.html` — Welfare-AI Research Brief v0.2 (2026-05-20)

**MiroFish 기반 LLM-에이전트 사회 시뮬레이션 × 사회복지 이론 — 박사 진학용 연구 주제 탐색 보고서**

12개 기반·주변 방법론 논문 + 7개 사회복지 학술 이론을 결합해 **19개 연구 주제 후보**를 5 클러스터로 정리한 strategy brief.

#### 방법론 backbone (12편)

- **LLM-에이전트 사회 시뮬레이션 계보**: Generative Agents (Park 2023) · CAMEL (Li 2023) · S3 (Gao 2023) · OASIS (CAMEL-AI 2024)
- **합성 페르소나 계열**: *Out of One, Many* (Argyle 2022) · *LLM Agents Grounded in Self-Reports* (2024) · *Cross-Cultural Survey Simulation with Calibrated Value Personas* (2026)
- **Boundary / validity**: *LLM-Based Social Simulations Require a Boundary* (2026) · *AI Agents Alone Are Not Yet Sufficient* (2026) · *LLM Social Simulations Are a Promising Research Method* (2026)
- **사회복지 ABM**: Sage 2019 외 2편
- **데이터셋**: [Nemotron-Personas-Korea](https://huggingface.co/datasets/nvidia/Nemotron-Personas-Korea) (NVIDIA, 1M records / 7M personas / 252 districts)

#### 사회복지 이론 backbone (7개 · v0.2 신규)

| Theory | Anchor |
| --- | --- |
| Self-efficacy / political efficacy | Bandura 1977 · Easton |
| Administrative Burden (3 dimensions) | Herd & Moynihan 2018 |
| CARIN Deservingness | van Oorschot 2000 |
| Policy Feedback | Mettler 2011 · Pierson 1993 |
| Non-Take-Up (3-stage) | van Oorschot 1991 · Currie 2006 |
| Stigma Management | Goffman 1963 · Spicker 1984 |
| Collective Efficacy | Sampson, Raudenbush & Earls 1997 |

#### 5 clusters · 19 topics

- **α** 합성 페르소나 방법론 (T4, T5, T9, T11)
- **β** 사회복지 응용 (T1, T2, T7, T8)
- **γ** 정보·환경 디자인 (T3, T6, T10)
- **δ** 사회복지사 의사결정 (T12)
- **ε** 사회복지 이론 기반 효능·태도·수용성 (T13–T19) — v0.2 신규

#### Recommended TOP 3

1. **T14 (Administrative Burden) × T1 (신청 여정) 결합** — CS workshop paper + 사회복지 학술지 paper 동시 산출
2. **T15 CARIN deservingness 한국 cross-section** — 가장 신선
3. **T4 algorithmic fidelity 한국 적용** — plan B 방법론

---

## 🛠 Tech notes

- 단일 파일 정적 HTML. JS는 TOC active highlight 한 줄뿐.
- 모바일 반응형 (breakpoints: 960px / 640px / 420px).
- 인쇄용 CSS 포함.
- 외부 의존성 없음.

GitHub Pages를 켜면 `https://<user>.github.io/phd-prep-research-notes/` 로 바로 열린다.

---

## 📌 사용 안내

본 자료는 **개인 연구 탐색 노트**이며 외부 학술 인용을 의도하지 않는다.
보고서 안에서 정리한 framing(예: *population-calibrated synthetic personas*, *validity boundary*, *administrative burden in simulated welfare journeys*, *collective qualitative patterns*)만 차용해 주세요.

— Lee Ju-ho · 2026-05-20
