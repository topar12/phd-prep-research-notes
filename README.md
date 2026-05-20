# phd-prep-research-notes

박사 진학(미국 박사 어드미션) 준비 과정에서 작성한 **연구 주제 탐색 노트** 모음.
Personal research-strategy briefs written while preparing for U.S. PhD applications.

---

## 📄 Contents

이 저장소에는 두 개의 보고서가 있습니다. 같은 연구 방향을 **두 가지 독자**에 맞춰 정리했습니다.

### `index.html` — Technical Research Brief (v0.2)

**MiroFish 기반 LLM-에이전트 사회 시뮬레이션 × 사회복지 이론 — 박사 진학용 연구 주제 탐색 보고서**

CS·HCI·CSS 시각으로 정리한 보고서. 방법론(LLM-agent simulation, synthetic persona, boundary conditions)과 사회복지 이론을 결합해 **19개 연구 주제**를 5 클러스터로 탐색.

- 방법론 backbone: Generative Agents · CAMEL · S3 · OASIS · Out of One Many · Self-Reports Grounding · Cross-Cultural Calibration · Boundary papers
- 사회복지 이론 backbone: Bandura · Herd&Moynihan · van Oorschot · Mettler · Goffman/Spicker · Sampson
- 평가축: 박사 어드미션 fit · 사회복지 가치 · 신선함 · 1년 PoC · 데이터 리스크 · 이론 anchor

### `domain-brief.html` — Social Welfare Domain Brief (v1.2)

**박사 가서 하려는 사회복지 AI 연구 주제 — 사회복지 이론과 한국 데이터로 본 열세 가지 후보**

사회복지학자/도메인 전문가용으로 다시 쓴 버전. 기술 용어·시뮬레이션 내부 메커니즘은 빼고, **"어떤 사회복지 질문을 다룰 수 있고 어떤 한국 데이터로 검증할 수 있는가"**의 관점으로만. 한국어 중심, 더 큰 글꼴, serif 타이포.

- **13개 논문 주제**를 4 클러스터로 정리: 복지 신청·비수급(3) · 정책 커뮤니케이션과 시민 인식(3) · 사회복지 실무 접점(4) · 사회복지 시스템·지역사회·알고리즘(3)
- 각 주제별로 무엇을 보는지, 어떻게 적용되는지(가상 시나리오 예시 포함), 한국 데이터로 어떻게 검증하는지, 왜 publishable한지
- 한국 학술 자료 anchor: 허용창 외(2020) 비수급 동태적 모델 · Campbell&Ahn(2023) 한국 burden tolerance · Baekgaard et al.(2025) 한국 포함 7개국 척도 · 이병규(2024) · 홍승헌·황하(2024) · 강신원(2023)
- 참고문헌 35편, 모두 자동 검증 프로세스 거침 (저자·연도·DOI 확인)

---

## 🔗 어떤 걸 먼저 보면 좋은가

- **사회복지·정책 시각**: `domain-brief.html` → 13개 논문 후보를 빠르게 훑고 흥미 있는 것부터.
- **방법론·CS·HCI 시각**: `index.html` → MiroFish 계보의 위치, 합성 페르소나의 algorithmic fidelity, boundary condition.
- **둘 다 읽기**: 같은 19개(혹은 13개) 주제를 두 시각에서 본 셈이 됩니다.

GitHub Pages를 켜면 `https://topar12.github.io/phd-prep-research-notes/` 가 `index.html`로 떠서 바로 열립니다. `domain-brief.html`은 별도 path로 접근.

---

## 🛠 Tech notes

- 단일 파일 정적 HTML. JS는 TOC active highlight 한 줄(`index.html`)만.
- 모바일 반응형 — breakpoints: 960px / 720px / 640px / 420px.
- 인쇄용 CSS 포함.
- 외부 의존성 없음.

---

## 📌 사용 안내

본 자료는 **개인 연구 탐색 노트**이며 외부 학술 인용을 의도하지 않습니다.
보고서 안에서 정리한 framing(예: *population-calibrated synthetic personas*, *validity boundary*, *administrative burden in simulated welfare journeys*, *collective qualitative patterns*)만 차용해 주세요.

— Lee Ju-ho · 2026-05-20
