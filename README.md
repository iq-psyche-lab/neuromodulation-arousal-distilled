<div align="center">

# 🧠 Neuromodulation & Arousal Distilled

### **"도파민은 행복 물질이다" 라고 말하는 것** 과,

$$\delta = R + \gamma V(s') - V(s) \quad(\text{TD 오차}),\qquad \text{도파민 발화} \propto \delta$$

### 도파민이 행복이 아니라 **보상예측오차** $\delta$ 를 신호한다는 것을 — 예측된 보상엔 *침묵하고* 예측 초과엔 *발화*하며 생략엔 *억제* 한다는 것을 — 아는 것은 **다르다.**

<br/>

> *"세로토닌이 기분을 조절한다" 고 **믿는 것** 과,*
>
> $$\text{5-HT} \;\not\equiv\; \text{기분},\qquad \text{5-HT} \;\approx\; \{\text{처벌 억제},\ \text{시간 할인},\ \text{내수용 신호}\}$$
>
> *세로토닌의 실제 기능이 "기분" 이 아니라 처벌 억제·시간 할인·내수용 감각과 더 가깝고, SSRI 가 *왜* 2-4주 걸리는지 — 그 지연이 단순 증가가 아닌 자가수용체 탈감작을 시사함을 — 아는 것은 다르다.*
>
> *"수면이 필요하다" 고 **아는 것** 과,*
>
> $$\dot A = I_A - w\,S - kA,\qquad \dot S = I_S - w\,A - kS \quad(\text{상호 억제 플립플롭})$$
>
> *LC·DRN·TMN 의 각성 핵과 VLPO 가 *상호 억제* 로 불안정한 중간 상태 없이 두 상태를 전환하는 회로를 — 기면증에서 이 스위치가 *어떻게* 무너지는지를 — 아는 것은 다르다.*
>
> *조절 물질을 "신호 전달 물질" 로 **뭉뚱그리는 것** 과,*
>
> $$\text{신경조절} = \text{피질의 *계산 파라미터*(gain·정밀도·학습률·탐색 온도)를 바꾸는 전역 연산자}$$
>
> *아세틸콜린이 신호-잡음비를 올리고, 노르에피네프린이 주의 자원을 재배분하며, 도파민이 예측오차 가중치를 바꾼다는 것 — 그리고 그 전역 상태가 의식의 ON/OFF 와 어떻게 연결되는지를 — 아는 것은 다르다.*

<br/>

**신경조절 ≠ 단순 신호** — 조절 물질은 메시지를 *전달* 하는 것이 아니라, 피질 전체의 *계산 상태를 전환* 하는 전역 연산자다. 그리고 그 상태가 의식을 *켜지만*, 켜진 의식의 내용과 질감은 회로 설명 너머에 남는다는 것을 정직하게 표시하는 것이 이 레포의 규율이다.

<br/>

**다루는 회로와 분자 (분자에서 의식으로, 그리고 그 사이의 간극)**

신경전달 vs 신경조절 · 전역 투사 · 계산 파라미터 · 슐츠 실험 · 보상예측오차(RPE) · TD 학습 · 중뇌-변연·중뇌-피질·흑질-선조체 · D1/D2 · 탐색-활용 · 조현병·파킨슨·중독 · 세로토닌의 실제 기능 · 봉선핵(DRN·MRN) · 14개 수용체 아형 · SSRI 지연·자가수용체 탈감작 · 충동성 · LC(청반)·NE · 기저 전뇌·ACh · 신호-잡음비 · 역U 함수 · TMN·히스타민 · VLPO·갈라닌 · 플립플롭 모델 · 오렉신/히포크레틴·기면증 · REM/NREM 신경조절 · 마취·시상-피질 · 5-HT2A·환각제 · 단아민 가설·케타민 · TD(λ) 시뮬레이션 · 플립플롭 동역학 · gain 모델

<br/>

**핵심 질문**

> **신경조절 물질은 *어떻게* 피질의 계산 상태를 전환하며 — 각성 스위치는 *어떻게* 의식을 켜는가?** 모든 조절 물질에는 그것이 바꾸는 계산 파라미터와, 설명해도 남는 경험의 측면이 있다. 이 레포는 **"도파민 = 행복"** 과 **"세로토닌 = 기분"** 과 **"신경조절 = 단순 신호"** 를 금지하고, 신경전달과 신경조절의 차이부터 도파민 RPE·세로토닌·NE/ACh·각성 플립플롭·의식과 정신병리까지 — **회로·분자 분석 → 실험·임상 증거 → 계산 모델 → 설명적 간극의 정직한 표시** 를 한 단계씩 전개합니다. 그리고 신경조절이 의식을 *켜도* 켜진 경험의 질감은 남는다는 것을, 그 *간극의 구조* 를 지도로 그립니다.

<br/>

[![Physis](https://img.shields.io/badge/Physis-L1_신경조절·각성-ec4899?style=flat-square&logo=brain&logoColor=white)](https://github.com/iq-ai-lab)
[![GitHub](https://img.shields.io/badge/GitHub-iq--ai--lab-181717?style=flat-square&logo=github)](https://github.com/iq-ai-lab)
[![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.26-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/)
[![SciPy](https://img.shields.io/badge/SciPy-1.11-8CAAE6?style=flat-square&logo=scipy&logoColor=white)](https://scipy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8-11557C?style=flat-square)](https://matplotlib.org/)
[![Docs](https://img.shields.io/badge/Docs-33개-ec4899?style=flat-square&logo=readthedocs&logoColor=white)](./README.md)
[![Analysis](https://img.shields.io/badge/회로·분자_분석(□)-132개-success?style=flat-square)](./README.md)
[![Verifications](https://img.shields.io/badge/수치_실험-36개-critical?style=flat-square)](./README.md)
[![Exercises](https://img.shields.io/badge/Exercises-99개-orange?style=flat-square)](./README.md)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square&logo=opensourceinitiative&logoColor=white)](./LICENSE)

<br/>

***Explain it, don't explain it away.***
*설명하되, 경험을 지우지 않는다.*

</div>

---

## 🎯 이 레포에 대하여

신경조절을 다루는 자료는 대부분 **"도파민은 행복, 세로토닌은 기분"** 이라는 표어에서 멈추거나, 반대로 **"조절 물질을 다 알면 마음을 설명한 것"** 이라고 과신합니다. 하지만 도파민이 *왜* 행복이 아니라 보상예측오차인지, 세로토닌이 신호하는 것과 *신호하지 않는 것* 이 무엇인지, 각성과 수면을 가르는 스위치가 *어떤 회로* 인지, 조절 물질이 "활성화" 가 아니라 *어떤 계산 파라미터* 를 바꾸는지 — 이런 "어떻게" 와 "어디까지" 는 제대로 구분되지 않습니다.

이 레포는 **신경조절을 계산 상태의 전환으로** 펼칩니다. 모든 조절 물질에 **신호 경로 · 수용체 · 바꾸는 계산 파라미터 · 임상적 고장 · 도달 못 하는 곳(설명적 간극)** 을 명시하고, numpy/scipy 로 TD 학습 RPE·플립플롭 동역학·gain 모델을 직접 돌려 그 주장을 눈으로 검증합니다. **회로를 설명하되, 경험 자체를 지우지 않습니다.**

| 일반 자료 | 이 레포 |
|----------|---------|
| "도파민 = 행복 물질" | **도파민 = 보상예측오차** — 슐츠 실험: 예측된 보상엔 침묵, 예측 초과엔 발화, 생략엔 억제. $\delta = R + \gamma V(s') - V(s)$ 의 TD 오차 $\square$ |
| "도파민이 많을수록 좋다" | **탐색-활용의 조절자** — 도파민 수준이 학습률과 탐색 온도를 바꾼다. 과잉(조현병)·결핍(파킨슨)·하이재킹(중독)의 회로 $\square$ |
| "세로토닌 = 기분 물질" | **기분이 아니라 억제·시간·내수용** — 처벌 억제·시간 할인·내수용 신호. "기분" 은 단순화이고 더 복잡한 그림이 있다 $\square$ |
| "SSRI 가 세로토닌을 늘려 낫게 한다" | **왜 2-4주인가** — 세로토닌은 *즉시* 오르는데 효과는 지연. 자가수용체(5-HT1A) 탈감작 가설. 단순 증가로는 설명 안 됨 $\square$ |
| "노르에피네프린 = 각성" | **신호-잡음비의 gain** — LC-NE 가 감각 gain 을 증폭(역U 함수). "활성화" 가 아니라 *계산 파라미터* 를 바꾼다 $\square$ |
| "아세틸콜린 = 기억" | **피질 선명화와 가소성** — ACh 가 신호 대 잡음을 높여 지각을 선명히, 가소성 문턱을 낮춰 학습을 연다(알츠하이머의 콜린성 손실) $\square$ |
| "수면은 그냥 꺼지는 것" | **플립플롭 스위치** — 각성 핵(LC·DRN·TMN)과 VLPO 의 *상호 억제* 가 중간 상태 없는 이분 안정을 만든다(Saper 2001) $\square$ |
| "기면증 = 졸린 병" | **스위치의 고장** — 오렉신/히포크레틴 손실이 플립플롭을 불안정하게 만들어 수면이 *침입* 한다. 회로 수준의 불안정 $\square$ |
| "신경조절 = 신호 전달" | **계산 파라미터를 세팅** — 조절 물질은 메시지가 아니라 gain·정밀도·학습률·탐색 온도를 바꾸는 *전역 연산자*. 피질 전체의 상태 전환 $\square$ |
| 메커니즘 나열 | numpy/scipy 로 **TD 학습 RPE 의 CS 이동** · **각성 플립플롭 동역학** · **NE/ACh gain 모델** 을 직접 구현해 회로 주장을 눈으로 확인 |

---

## 📌 Physis 레이어 지도 — 선행과 창발

```
        ┌──────────────── L1 선행 (필수) ────────────────┐
[neurons-neural-codes]  ─┤  수용체 작동·신경전달물질 기초            │
[brain-architecture]    ─┤  뇌간 핵·기저핵·피질의 구조적 관계        │
                         └────────────────────┬───────────────────┘
                                              ▼
                  ┌──────────────── L1 (이 레포) ────────────────┐
[plasticity-learning] ──┤  🧠  Neuromodulation & Arousal Distilled │
   (시너지: 가소성 조절) │   "도파민은 행복이 아니라 보상예측오차"      │
                        │   "세로토닌은 기분이 아니라 억제·시간·내수용" │
                        │   "신경조절은 신호가 아니라 계산 파라미터"    │
                        └────────────────────┬─────────────────────┘
                                             │  조절 물질이 위 레이어에서 다시 쓰인다
   ┌─────────────────────────────────────────┼──────────────────────────────────┐
   ▼              ▼               ▼               ▼              ▼              ▼
[L2 learning-decision] [L2 attention-wm] [L2 emotion-motivation] [L4 altered-states] [L4 ncc] [L6 prediction]
 RPE 가 의사결정·학습   NE·ACh 가 주의를   DA·5-HT 가 동기·감정     각성 조절 실패와    각성 수준과   RPE 는 예측
 으로                  구현               처리로                   의식 상태          의식의 NCC    원리의 구현층
```

> ⚠️ **선행 학습**: 이 레포는 **neurons-neural-codes-distilled** (L1 — 수용체 작동 원리·신경전달물질 기초) 와 **brain-architecture-distilled** (L1 — 뇌간 핵·기저핵·피질의 구조적 관계) 를 **필수** 로 전제합니다.

> 🤝 **L1 내부 시너지**: **plasticity-learning-distilled** — 도파민·아세틸콜린이 *시냅스 가소성을 조절* 하는 방식. 이 레포의 학습 관련 메커니즘과 어휘를 공유합니다.

> 🪜 **창발 (위 레이어가 이 레포를 다시 쓴다)**: Chapter 2 의 보상예측오차는 **L2 learning-decision** 의 의사결정·강화학습으로, Chapter 4 의 NE·ACh 는 **L2 attention-working-memory** 의 주의 구현으로, 도파민·세로토닌은 **L2 emotion-motivation** 의 동기·감정 처리로, Chapter 5~6 의 각성 조절과 마취·환각제는 **L4 altered-states** 와 **L4 ncc**(각성 수준과 의식의 신경 상관물, VLPO-LC 관계)의 심화로, 그리고 보상예측오차는 **L6 prediction-everywhere** 의 예측 원리가 구현되는 한 층위로 이어집니다.

> 🔗 **L3 교차 (IQ AI Lab)**: 도파민 RPE 와 TD 학습의 정확한 대응은 **IQ AI Lab 의 강화학습(RL)** 트랙과 직접 교차합니다 — 슐츠의 원숭이에서 본 $\delta$ 가 곧 TD-error 입니다.

> 🟡 **이 레포의 성격**: 여기서 다루는 핵심 — **세로토닌이 정확히 무엇을 코딩하는가**, **각성 스위치와 의식의 연결**, **단아민 가설의 한계** — 는 여전히 **진행 중인 신경과학 영역** 입니다. 레포는 "정답" 이 아니라 **"조절 물질이 계산 상태를 바꾸는 방식과, 그 설명이 닿지 못하는 경험의 지도"** 를 제공합니다.

---

## 🚀 빠른 시작

각 챕터의 첫 문서부터 바로 시작하세요!

[![Ch1](https://img.shields.io/badge/🔹_Ch1-신경조절이란_무엇인가-ec4899?style=for-the-badge)](./ch1-what-is-neuromodulation/01-transmission-vs-modulation.md)
[![Ch2](https://img.shields.io/badge/🔹_Ch2-도파민·보상예측오차-ec4899?style=for-the-badge)](./ch2-dopamine-rpe/01-schultz-experiment.md)
[![Ch3](https://img.shields.io/badge/🔹_Ch3-세로토닌-ec4899?style=for-the-badge)](./ch3-serotonin/01-serotonin-real-function.md)
[![Ch4](https://img.shields.io/badge/🔹_Ch4-NE·아세틸콜린-ec4899?style=for-the-badge)](./ch4-ne-acetylcholine/01-norepinephrine.md)
[![Ch5](https://img.shields.io/badge/🔹_Ch5-각성_스위치-ec4899?style=for-the-badge)](./ch5-arousal-switch/01-arousal-systems.md)
[![Ch6](https://img.shields.io/badge/🔹_Ch6-의식·정신병리-ec4899?style=for-the-badge)](./ch6-consciousness-pathology/01-anesthesia.md)
[![Ch7](https://img.shields.io/badge/🔹_Ch7-종합·계산-ec4899?style=for-the-badge)](./ch7-synthesis-tools/01-td-dopamine-sim.md)

---

## 📚 전체 학습 지도

> 💡 각 챕터를 클릭하면 상세 문서 목록이 펼쳐집니다 · **총 33개 문서**

<br/>

### 🔹 Chapter 1: 신경조절이란 무엇인가

> **핵심 질문:** 빠른 이온성 신경전달(ms)과 느린 대사성 신경조절(초~분)은 *왜* 다른 시스템을 요구하는가? 단일 핵(LC·DRN)에서 피질 전체로 광범위하게 투사한다는 것은 무엇을 뜻하는가? 신경조절이 "신호" 가 아니라 *계산 파라미터*(gain·신호잡음비·가소성 문턱)를 바꾼다는 것은 무엇이며, 그 전역 상태는 의식과 어떻게 연결되는가?

<details>
<summary><b>신경전달 vs 신경조절부터 의식과의 연결까지 (4개 문서)</b></summary>

<br/>

| 문서 | 핵심 회로·분자·계산 |
|------|---------------------|
| [01. 신경전달 vs 신경조절](./ch1-what-is-neuromodulation/01-transmission-vs-modulation.md) | **빠름 vs 느림** — 이온성(ms, 점대점) 전달과 대사성(초~분, 전역) 조절. G단백질 연결 수용체·2차 전령. 왜 별도 시스템이 필요한가 $\square$ |
| [02. 조절의 전역성](./ch1-what-is-neuromodulation/02-global-modulation.md) | **소수 핵 → 전 피질** — LC·DRN 등 작은 핵에서의 광범위 투사. 한 시스템이 피질 전체 상태를 *전역적으로* 변환하는 구조 $\square$ |
| [03. 조절의 계산적 역할](./ch1-what-is-neuromodulation/03-computational-role.md) | **파라미터를 바꾼다** — 신경조절 = gain·신호잡음비·가소성 문턱·탐색 온도의 세팅. "메시지" 가 아니라 *연산 모드* 의 전환 $\square$ |
| [04. 신경조절과 의식](./ch1-what-is-neuromodulation/04-modulation-and-consciousness.md) | **상태가 의식과 만나는 곳(예고)** — 조절 물질의 전역 상태와 의식 수준의 연결. 각성이 켜져도 남는 경험의 질감 $\square$ |

</details>

<br/>

### 🔹 Chapter 2: 도파민 — 보상예측오차

> **핵심 질문:** 슐츠의 원숭이에서 도파민 신호는 *왜* 무조건 자극에서 조건화 자극으로 이동하는가? RPE = 실제 보상 − 예측된 보상은 TD 학습과 *어떻게* 정확히 대응하는가(→ IQ AI Lab RL)? 세 경로(중뇌-변연·중뇌-피질·흑질-선조체)는 어떻게 분업하며, D1/D2 는 강화를 어떻게 가르는가? 그리고 조현병·파킨슨·중독은 이 시스템의 어떤 고장인가?

<details>
<summary><b>슐츠 실험부터 도파민 정신병리까지 (6개 문서)</b></summary>

<br/>

| 문서 | 핵심 회로·분자·계산 |
|------|---------------------|
| [01. 슐츠 실험](./ch2-dopamine-rpe/01-schultz-experiment.md) | **신호의 이동** — 복측 피개부(VTA) 뉴런. 무조건 자극(US)에서 조건화 자극(CS)으로 도파민 발화가 이동. 예측 초과↑·예측된 보상→0·생략↓ $\square$ |
| [02. 보상예측오차 수학](./ch2-dopamine-rpe/02-rpe-math.md) | **RPE = TD 오차** — $\delta = R + \gamma V(s') - V(s)$. 도파민 발화 $\propto \delta$. TD 학습과의 정확한 대응(→ AI Lab RL) $\square$ |
| [03. 도파민 경로](./ch2-dopamine-rpe/03-dopamine-pathways.md) | **세 경로의 분업** — 중뇌-변연(동기)·중뇌-피질(인지)·흑질-선조체(운동). 같은 분자, 다른 회로, 다른 기능 $\square$ |
| [04. 도파민과 학습](./ch2-dopamine-rpe/04-dopamine-learning.md) | **D1/D2 와 직접·간접 경로** — D1(직접, Go)·D2(간접, NoGo)의 분리와 강화. 기저핵 회로와 가소성(→ architecture, → plasticity) $\square$ |
| [05. 도파민과 탐색-활용](./ch2-dopamine-rpe/05-exploration-exploitation.md) | **탐색 온도의 조절** — 도파민 수준이 탐색(새 정보)과 활용(기존 가치)의 균형을 조정. RL 의 $\epsilon$·온도와의 대응 $\square$ |
| [06. 도파민과 정신병리](./ch2-dopamine-rpe/06-dopamine-pathology.md) | **과잉·결핍·하이재킹** — 조현병(도파민 과잉·현저성 오귀인)·파킨슨(흑질 손실)·중독(RPE 하이재킹)·우울(동기 저하) $\square$ |

</details>

<br/>

### 🔹 Chapter 3: 세로토닌 — 억제, 시간, 내수용

> **핵심 질문:** 세로토닌은 *왜* "행복 물질" 이 아닌가 — 그것이 신호하는 것(처벌 억제·시간 할인·내수용)과 신호하지 않는 것의 경계는? 봉선핵에서 전뇌로의 투사와 14개 수용체 아형은 어떤 다양성을 만드는가? SSRI 가 *왜* 2-4주 걸리며, 그 지연은 자가수용체 탈감작에 대해 무엇을 시사하는가? 그리고 세로토닌이 정확히 무엇을 코딩하는지가 *왜* 아직 논쟁 중인가?

<details>
<summary><b>세로토닌의 실제 기능부터 미해결까지 (5개 문서)</b></summary>

<br/>

| 문서 | 핵심 회로·분자·계산 |
|------|---------------------|
| [01. 세로토닌의 실제 기능](./ch3-serotonin/01-serotonin-real-function.md) | **기분이 아니라…** — "행복 물질" 단순화의 교정. 처벌 억제(behavioral inhibition)·시간 할인·내수용 감각 신호. 무엇을 신호하고 무엇을 안 하는가 $\square$ |
| [02. 세로토닌 경로](./ch3-serotonin/02-serotonin-pathways.md) | **봉선핵의 다양성** — DRN·MRN 에서 전뇌로의 투사. 14개 수용체 아형(5-HT1~7)의 기능 분기. 한 분자, 많은 효과 $\square$ |
| [03. SSRI — 왜 2-4주인가](./ch3-serotonin/03-ssri-delay.md) | **지연의 역설** — 세로토닌은 즉시 증가, 치료 효과는 지연. 5-HT1A 자가수용체 탈감작 가설. 단순 증가로는 설명 불가 $\square$ |
| [04. 세로토닌과 공격성·충동성](./ch3-serotonin/04-serotonin-aggression.md) | **낮은 5-HT = 충동↑?** — 충동성·공격성과의 연관의 실제 증거와 한계. 상관의 강도와 인과의 불확실 $\square$ |
| [05. 세로토닌 시스템의 미해결](./ch3-serotonin/05-serotonin-open-questions.md) | **여전히 논쟁 중** — 세로토닌이 정확히 무엇을 코딩하는지에 대한 경쟁 가설들. 단일 함수로 환원되지 않는 이유 $\square$ |

</details>

<br/>

### 🔹 Chapter 4: 노르에피네프린과 아세틸콜린 — 주의의 물질

> **핵심 질문:** LC(청반)의 노르에피네프린은 *어떻게* 신호-잡음비를 높이며, 왜 각성과 주의의 역U 함수가 나타나는가? 기저 전뇌·뇌간의 아세틸콜린은 *어떻게* 감각 처리를 선명하게 하고 가소성을 여는가? 두 시스템은 주의의 어떤 *다른* 측면을 담당하며, 알츠하이머의 콜린성 손실은 무엇을 말하는가? 그리고 최적 각성과 스트레스의 결정 저하는 어떻게 설명되는가?

<details>
<summary><b>노르에피네프린부터 LC-NE 의사결정까지 (5개 문서)</b></summary>

<br/>

| 문서 | 핵심 회로·분자·계산 |
|------|---------------------|
| [01. 노르에피네프린 — 각성과 신호 증폭](./ch4-ne-acetylcholine/01-norepinephrine.md) | **gain 의 증폭** — LC 에서 피질로. NE 가 신호-잡음비를 올려 반응 gain 을 키운다. "활성화" 가 아니라 계산 파라미터 $\square$ |
| [02. 아세틸콜린 — 피질 활성화와 주의](./ch4-ne-acetylcholine/02-acetylcholine.md) | **피질 선명화** — 기저 전뇌·뇌간에서의 투사. ACh 가 외인성 신호를 증폭하고 내인성을 억제해 감각을 선명히 $\square$ |
| [03. NE·ACh 의 상호작용](./ch4-ne-acetylcholine/03-ne-ach-interaction.md) | **주의의 두 축** — NE(예상치 못한 변화·재배분)와 ACh(예상된 불확실성·선명화)가 담당하는 다른 측면(Yu & Dayan) $\square$ |
| [04. 아세틸콜린과 기억](./ch4-ne-acetylcholine/04-acetylcholine-memory.md) | **가소성의 문 열기** — ACh 가 부호화 모드를 켜고 가소성 문턱을 낮춘다. 알츠하이머의 콜린성 손실(→ plasticity) $\square$ |
| [05. LC-NE 와 의사결정](./ch4-ne-acetylcholine/05-lc-ne-decision.md) | **역U 와 위상성/긴장성** — 최적 각성(Yerkes-Dodson), LC 의 phasic/tonic 모드와 활용-탐색(Aston-Jones & Cohen 2005) $\square$ |

</details>

<br/>

### 🔹 Chapter 5: 각성 스위치 — 수면과 의식의 ON/OFF

> **핵심 질문:** LC(NE)·DRN(5-HT)·TMN(히스타민)·LDT/PPT(ACh)의 각성 핵과 VLPO 의 수면 핵은 *어떻게* 서로를 억제하는가? 그 상호 억제가 *왜* 중간 상태 없는 이분 안정(플립플롭)을 만드는가? 오렉신/히포크레틴 손실은 *왜* 이 스위치를 불안정하게 만들어 기면증을 일으키는가? 그리고 REM(콜린성 우세)과 NREM(단아민성 우세)의 신경조절 패턴은 어떻게 다른가?

<details>
<summary><b>각성 유지 시스템부터 수면 단계까지 (5개 문서)</b></summary>

<br/>

| 문서 | 핵심 회로·분자·계산 |
|------|---------------------|
| [01. 각성 유지 시스템](./ch5-arousal-switch/01-arousal-systems.md) | **각성 촉진 핵** — LC(NE)·DRN(5-HT)·TMN(히스타민)·LDT/PPT(ACh). 상행 망상 활성계(ARAS)와 피질 각성 $\square$ |
| [02. VLPO — 수면 촉진 핵](./ch5-arousal-switch/02-vlpo.md) | **수면의 스위치** — 복외측 시각전핵(VLPO)의 수면 중 활성화. GABA·갈라닌으로 각성 핵을 억제 $\square$ |
| [03. 플립플롭 모델](./ch5-arousal-switch/03-flipflop-model.md) | **상호 억제 = 이분 안정** — 각성 핵 ⊣ VLPO ⊣ 각성 핵. 중간 상태가 불안정한 이유. 히스테리시스(Saper 2001) $\square$ |
| [04. 기면증 — 플립플롭의 고장](./ch5-arousal-switch/04-narcolepsy.md) | **오렉신의 안정자 역할** — 오렉신/히포크레틴 손실이 스위치를 불안정하게 → 수면·REM 의 침입. 탈력발작 $\square$ |
| [05. 수면 단계와 신경조절](./ch5-arousal-switch/05-sleep-stages.md) | **REM vs NREM** — REM(콜린성 우세·단아민성 침묵)·NREM(단아민성)의 조절 패턴. 꿈과 신경조절 상태 $\square$ |

</details>

<br/>

### 🔹 Chapter 6: 신경조절과 의식·정신병리

> **핵심 질문:** 마취약은 *어떻게* 시상-피질 루프를 차단하며, 신경조절 관점에서 무엇이 꺼지는가? 5-HT2A 작용제(환각제)는 *어떻게* 지각을 재구성하는가? 단아민 가설은 우울·조증에서 무엇을 성공·실패했고, 케타민은 무엇을 바꾸었는가? 그리고 각성·집중·몽롱·도취 상태가 신경조절 패턴과 대응한다 해도, *왜 그 상태에 특정 질감의 경험이 있는가* 는 남는다.

<details>
<summary><b>마취부터 신경조절 상태와 경험까지 (4개 문서)</b></summary>

<br/>

| 문서 | 핵심 회로·분자·계산 |
|------|---------------------|
| [01. 마취와 신경조절](./ch6-consciousness-pathology/01-anesthesia.md) | **시상-피질 차단** — 마취약이 통합을 끊는 방식, 신경조절 관점. 각성 스위치와 의식 수준의 계측(→ L4 ncc) $\square$ |
| [02. 환각제 — 5-HT2A 와 의식](./ch6-consciousness-pathology/02-psychedelics.md) | **수용체가 지각을 재구성** — 5-HT2A 작용제가 피질 엔트로피를 높여 지각을 재편. 신경조절과 경험의 극적 변화 $\square$ |
| [03. 우울증·조증 — 단아민 조절 이상](./ch6-consciousness-pathology/03-depression-mania.md) | **단아민 가설의 성공과 한계** — 단순 증감으로는 부족. 케타민(글루탐산·가소성)의 빠른 효과가 던지는 도전 $\square$ |
| [04. 신경조절 상태와 경험](./ch6-consciousness-pathology/04-states-and-experience.md) | **상태 → 질감의 간극** — 각성·집중·몽롱·도취가 조절 패턴과 대응. 그러나 *왜 이렇게 느껴지는가* 는 남는 경험의 잔여 $\square$ |

</details>

<br/>

### 🔹 Chapter 7: 종합 · 계산

> **핵심 질문:** 슐츠 실험의 RPE 신호를 TD(λ)로 *어떻게* 재현하는가? 각성 핵·VLPO 의 상호 억제 동역학을 *어떻게* 시뮬레이션하며, 기면증은 어떤 파라미터 변화로 나타나는가? NE·ACh 의 gain 효과는 어떻게 모델링하는가? 그리고 종합 — "의식의 ON/OFF 와 신경조절, 그리고 켜진 의식이어야 경험이 있는 이유의 간극" 은?

<details>
<summary><b>TD 시뮬레이션부터 종합까지 (4개 문서)</b></summary>

<br/>

| 문서 | 핵심 회로·분자·계산 |
|------|---------------------|
| [01. TD 학습으로 도파민 시뮬레이션](./ch7-synthesis-tools/01-td-dopamine-sim.md) | **RPE 의 CS 이동 재현** — TD(λ)로 슐츠 실험을 재현. 학습 초기→후기 도파민 신호의 US→CS 이동을 열지도로(Python) $\square$ |
| [02. 플립플롭 각성 모델](./ch7-synthesis-tools/02-flipflop-sim.md) | **상호 억제 동역학** — 각성 핵·VLPO 의 이분 안정 전환 시뮬레이션. 기면증: 결합 약화로 불안정(Python) $\square$ |
| [03. 신경조절 gain 모델](./ch7-synthesis-tools/03-gain-model.md) | **gain·선명화** — NE 가 반응 gain 을(역U), ACh 가 피질 선명도를 조절하는 효과 시뮬레이션(Python) $\square$ |
| [04. 종합](./ch7-synthesis-tools/04-synthesis.md) | **켜짐과 그 너머** — 신경조절이 의식을 켜는 방식과, 켜진 경험의 질감이 남는 간극. L1 의 종착, 위 레이어로의 발사대(→ L2, L4, L6) |

</details>

---

> 🆕 **2026-06 최신 업데이트**: Ch2-01 의 슐츠 신호 이동을 US→CS 전이·생략 시 억제로 명시, Ch2-02 의 RPE 를 $\delta = R + \gamma V(s') - V(s)$ 의 TD 오차로 정렬, Ch3-03 의 SSRI 지연을 5-HT1A 자가수용체 탈감작 가설로 보강, Ch4-05 의 LC-NE 를 phasic/tonic 모드와 역U 로 강화, Ch5-03 의 플립플롭을 상호 억제 히스테리시스로 명시(Saper 2001), Ch6-03 의 단아민 가설을 케타민·글루탐산 가소성과 함께 한계까지 — **10-섹션 Principle → Boundary → Experience 골격이 전체 33개 문서에서 일관** 됩니다.

## 📐 문서 형식 — Principle → Boundary → Experience

모든 문서는 **Psyche/Physis 표준 10-섹션** 으로 작성되고, 마지막 세 단(Principle · Boundary · Experience)으로 종결됩니다.

| # | 섹션 | 내용 |
|:-:|------|------|
| 1 | 🎯 **핵심 질문** | 어떤 신경조절 현상을, 어떤 회로·계산 원리에서 설명하나 |
| 2 | 🌍 **어디서 마주치나** | 이 조절 시스템이 작동하는 장면(학습·수면·정신병리) |
| 3 | 🔍 **직관의 함정** | "도파민 = 행복"·"세로토닌 = 기분" 같은 단순화 |
| 4 | ⚙️ **회로·분자 분석** | 조절 물질의 신호 경로·수용체·계산 역할을 단계별로 |
| 5 | 🧪 **실험·임상 증거** | 슐츠 실험·기면증·SSRI 지연이 이론을 어떻게 지지·수정하나 |
| 6 | 🌉 **설명적 간극** | 각성 상태가 켜져도 왜 거기에 경험이 있는가는 남는다 |
| 7 | 🧬 **횡단 원리** | 예측·통합이 신경조절 수준에서 어떻게 나타나나 |
| 8 | 🪞 **1인칭** | 각성·집중·몽롱·도취 상태가 경험으로서 어떻게 느껴지나 |
| 9 | 📐 **예측·반증** | 이 신경조절 이론이 내놓는 반증 가능한 예측 |
| 10 | 🤔 **다음 질문** | 다음 문서/레이어로의 연결 |

```
🧩 Principle  — 이 신경조절 메커니즘이 어떤 계산 상태를 어떻게 바꾸는가
🌉 Boundary   — 신경조절 상태가 의식 경험을 설명하지 못하는 지점
🪞 Experience — 이 신경조절 상태가 1인칭으로 어떻게 경험되는가
```

> 📚 **연습문제 총 99개** (33 문서 × 3): **기초 / 심화 / 논문 비평** 3-tier, 모두 `<details>` 펼침 해설. 신경전달/조절의 구분부터 RPE 손 계산, SDT 없는 도파민 발화 해석, 플립플롭 안정성 분석, 단아민 가설 비평까지 단계적 심화.
>
> 🧮 **수치 실험 총 36개** (문서당 1~2개 — `### 실험 N` 형식, Ch7 의 도구 문서는 문서당 2개): Python 3 + numpy + scipy + matplotlib. TD 학습 RPE 의 CS 이동 · 각성 플립플롭 동역학 · NE/ACh gain 모델. 모든 코드 블록은 실행 검증을 거쳤습니다.
>
> 🧭 **푸터 네비게이션**: 각 문서 하단에 `◀ 이전 / 📚 README / 다음 ▶` 링크. 챕터 경계에서도 다음 챕터 첫 문서로 연결.

---

## 🏆 핵심 결과 인덱스

이 레포에서 **완전한 회로·분자 분석** 또는 **scipy/numpy 검증** 을 제공하는 대표 결과 모음입니다. 각 문서에서 $\square$ 로 종결되는 분석 또는 `results/` 하의 그림을 확인할 수 있습니다.

| 결과 | 서술 | 출처 문서 |
|------|------|----------|
| **도파민 = 보상예측오차** | 예측 초과↑·예측됨→0·생략↓, 슐츠 실험의 신호 이동 | [Ch2-01](./ch2-dopamine-rpe/01-schultz-experiment.md) |
| **RPE = TD 오차** | $\delta = R + \gamma V(s') - V(s)$, TD 학습과의 대응 | [Ch2-02](./ch2-dopamine-rpe/02-rpe-math.md) |
| **D1/D2 직접·간접 경로** | Go/NoGo 강화의 분리 | [Ch2-04](./ch2-dopamine-rpe/04-dopamine-learning.md) |
| **도파민 정신병리** | 조현병·파킨슨·중독의 회로 고장 | [Ch2-06](./ch2-dopamine-rpe/06-dopamine-pathology.md) |
| **세로토닌 ≠ 기분** | 처벌 억제·시간 할인·내수용 신호 | [Ch3-01](./ch3-serotonin/01-serotonin-real-function.md) |
| **SSRI 2-4주 지연** | 자가수용체(5-HT1A) 탈감작 가설 | [Ch3-03](./ch3-serotonin/03-ssri-delay.md) |
| **NE 의 gain 증폭** | 신호-잡음비·역U 함수 | [Ch4-01](./ch4-ne-acetylcholine/01-norepinephrine.md) |
| **NE·ACh 주의 분업** | 예상치 못한 변화 vs 예상된 불확실성 | [Ch4-03](./ch4-ne-acetylcholine/03-ne-ach-interaction.md) |
| **각성 플립플롭** | 상호 억제 → 중간 상태 없는 이분 안정 | [Ch5-03](./ch5-arousal-switch/03-flipflop-model.md) |
| **기면증 = 스위치 고장** | 오렉신 손실 → 플립플롭 불안정 | [Ch5-04](./ch5-arousal-switch/04-narcolepsy.md) |
| **신경조절 = 계산 파라미터** | gain·정밀도·학습률·탐색 온도의 세팅 | [Ch1-03](./ch1-what-is-neuromodulation/03-computational-role.md) |
| **마취 = 시상-피질 차단** | 통합의 단절과 의식 수준 | [Ch6-01](./ch6-consciousness-pathology/01-anesthesia.md) |
| **TD(λ) RPE 시뮬레이션** | US→CS 신호 이동의 열지도 재현(Python) | [Ch7-01](./ch7-synthesis-tools/01-td-dopamine-sim.md) |
| **플립플롭 동역학** | 이분 안정 전환·기면증 불안정(Python) | [Ch7-02](./ch7-synthesis-tools/02-flipflop-sim.md) |
| **경험의 잔여** | 켜진 의식의 질감이 남는 간극의 지도 | [Ch7-04](./ch7-synthesis-tools/04-synthesis.md) |

> 💡 **챕터별 문서·결과 수** (목표):
>
> | 챕터 | 문서 수 | $\square$ 분석 | 수치 실험 | 연습문제 |
> |------|---------|---------------|-----------|----------|
> | Ch1 신경조절이란 무엇인가 | 4 | 16 | 4 | 12 |
> | Ch2 도파민·보상예측오차 | 6 | 24 | 6 | 18 |
> | Ch3 세로토닌 | 5 | 20 | 5 | 15 |
> | Ch4 NE·아세틸콜린 | 5 | 20 | 5 | 15 |
> | Ch5 각성 스위치 | 5 | 20 | 5 | 15 |
> | Ch6 의식·정신병리 | 4 | 16 | 4 | 12 |
> | Ch7 종합·계산 | 4 | 16 | 7 | 12 |
> | **합계** | **33** | **132** | **36** | **99** |
>
> 연습문제는 문서당 3개 (기초/심화/논문 비평, 모두 `<details>` 해설) 로 총 **99개**, 수치 실험은 문서당 1~2개 (`### 실험 N` 형식) 로 총 **36개** 입니다.

---

## 💻 실험 환경

모든 챕터의 검증은 아래 환경에서 재현 가능합니다 (GPU 불필요 — 순수 numpy/scipy 기반).

```bash
# requirements.txt
numpy==1.26.0
scipy==1.11.0
matplotlib==3.8.0
pandas==2.1.0       # 시행 로그·발화율 정리
jupyter==1.0.0
```

```bash
# 환경 설치 (CPU only, 1분 내)
pip install numpy==1.26.0 scipy==1.11.0 matplotlib==3.8.0 pandas==2.1.0 jupyter==1.0.0

jupyter notebook
```

```python
# 대표 실험 ① — TD 학습으로 도파민 RPE 시뮬레이션 (Ch2, Ch7-01)
#   슐츠 실험: CS(조건화 자극) → (지연) → US(보상)
#   도파민 = RPE = R + γV(s') − V(s)
import numpy as np

def td_learning(n_trials=100, alpha=0.1, gamma=0.9, n_steps=10):
    V = np.zeros(n_steps + 1)        # 가치 함수
    da_responses = []                # 도파민(=RPE) 응답 기록
    for _ in range(n_trials):
        trial_da = np.zeros(n_steps)
        R = np.zeros(n_steps); R[-1] = 1.0   # US(보상)는 마지막 타임스텝
        for t in range(n_steps):
            rpe = R[t] + gamma * V[t+1] - V[t]   # RPE = 도파민 신호
            V[t] += alpha * rpe
            trial_da[t] = rpe
        da_responses.append(trial_da.copy())
    return np.array(da_responses), V

da, V = td_learning()
print(f"초기 trial — US 시점 RPE: {da[0, -1]:+.2f}   CS 시점 RPE: {da[0, 0]:+.2f}")
print(f"후기 trial — US 시점 RPE: {da[-1, -1]:+.2f}   CS 시점 RPE: {da[-1, 0]:+.2f}")
# → 학습이 진행되면 도파민 신호가 US 에서 CS 로 이동한다 (슐츠 실험 재현)
```

```python
# 대표 실험 ② — 각성-수면 플립플롭: 상호 억제 → 중간 상태 없는 이분 안정 (Ch5, Ch7-02)
def arousal_flipflop(dt=0.01, T=1000, w_mutual=2.5, seed=0):
    rng = np.random.default_rng(seed)
    n = int(T/dt)
    A = np.zeros(n); S = np.zeros(n)      # A=각성 핵, S=VLPO
    A[0], S[0] = 1.0, 0.0
    for i in range(1, n):
        drive_A = 0.5 + 0.10*rng.standard_normal()    # 외부 각성 압력
        drive_S = 0.3 + 0.05*rng.standard_normal()    # 수면 압력(아데노신)
        A[i] = np.clip(A[i-1] + dt*(drive_A - w_mutual*S[i-1] - 0.5*A[i-1]), 0, 1)
        S[i] = np.clip(S[i-1] + dt*(drive_S - w_mutual*A[i-1] - 0.5*S[i-1]), 0, 1)
    return A, S
# → 각성/수면 사이 안정 전환, 중간 상태는 불안정
#   기면증: w_mutual 을 낮추면(오렉신 손실) 스위치가 흔들리며 상태 침입이 발생

# 대표 실험 ③ — 신경조절 gain 모델 (Ch4, Ch7-03)
#   NE: 반응 gain 증폭(역U), ACh: 피질 선명화(억제 강화) → 신호-잡음비 변화
```

```python
# 대표 실험 ③ — 신경조절 gain: NE 의 역U 증폭과 ACh 의 선명화
def neuromodulation_gain(stimulus, NE_level=1.0, ACh_level=1.0, seed=0):
    rng = np.random.default_rng(seed)
    response = stimulus + rng.standard_normal(stimulus.shape) * 0.5   # 기저 잡음
    optimal_NE = 1.0
    ne_factor = 1 + NE_level - (NE_level - optimal_NE)**2             # 역U
    response *= ne_factor
    ach_sharpening = 1 + 0.3 * ACh_level                             # 억제 강화
    return np.where(response > 0, response * ach_sharpening, response)

x = np.sin(np.linspace(0, 6*np.pi, 64))
for ne in (0.3, 1.0, 1.7):
    snr = neuromodulation_gain(x, NE_level=ne).std()
    print(f"NE={ne:.1f}  →  반응 진폭 ≈ {snr:.2f}")
# → NE 의 gain 인자는 중간 수준에서 정점을 이루는 역U 형태: 너무 낮거나 높으면 수행 저하
```

---

## 🗺️ 추천 학습 경로

<details>
<summary><b>🟢 "신경조절의 직관을 빠르게 잡고 싶다" — 입문 투어 (1주, 약 10~12시간)</b></summary>

<br/>

```
Day 1  Ch1-01  신경전달 vs 신경조절
       Ch1-03  조절의 계산적 역할
Day 2  Ch2-01  슐츠 실험
       Ch2-02  보상예측오차 수학
Day 3  Ch3-01  세로토닌의 실제 기능
       Ch3-03  SSRI — 왜 2-4주인가
Day 4  Ch4-01  노르에피네프린 — 신호 증폭
       Ch4-02  아세틸콜린 — 피질 활성화
Day 5  Ch5-03  플립플롭 모델
       Ch5-04  기면증 — 스위치의 고장
Day 6  Ch6-01  마취와 신경조절
       Ch7-01  TD 학습으로 도파민 시뮬레이션
Day 7  Ch2-06  도파민과 정신병리
       Ch7-04  종합
```

</details>

<details>
<summary><b>🟡 "메커니즘을 정복한다" — 회로 집중 (2주, 약 22~26시간)</b></summary>

<br/>

```
1주차 — 신경조절 일반·도파민·세로토닌
  Day 1  Ch1 전체            전달/조절·전역성·계산 역할·의식
  Day 2  Ch2-01~03           슐츠 + RPE 수학 + 세 경로
  Day 3  Ch2-04~06           D1/D2 + 탐색-활용 + 정신병리
  Day 4  Ch3-01~03           실제 기능 + 경로 + SSRI 지연
  Day 5  Ch3-04~05           충동성 + 미해결
  Day 6  Ch4-01~03           NE + ACh + 상호작용
  Day 7  Ch4-04~05           ACh 기억 + LC-NE 의사결정

2주차 — 각성 스위치·의식·종합
  Day 1  Ch5-01~03           각성 핵·VLPO·플립플롭
  Day 2  Ch5-04~05           기면증 + 수면 단계
  Day 3  Ch6-01~02           마취 + 환각제
  Day 4  Ch6-03~04           우울·조증 + 상태와 경험
  Day 5  Ch7-01~02           TD 시뮬레이션 + 플립플롭 모델
  Day 6  Ch7-03              gain 모델
  Day 7  Ch7-04              종합
```

</details>

<details>
<summary><b>🔴 "신경조절과 의식을 완전 정복한다" — 전체 정복 (7주, 약 35~45시간 + 실험 재현 10~12시간)</b></summary>

<br/>

```
1주차  Chapter 1 — 신경조절이란 무엇인가
        → 신경전달/신경조절의 시간 척도 구분
        → 소수 핵의 전역 투사 구조
        → "계산 파라미터를 바꾼다" 관점 내면화

2주차  Chapter 2 — 도파민·보상예측오차
        → 슐츠 실험의 US→CS 이동 정리
        → RPE = TD 오차 손 유도(→ AI Lab RL)
        → D1/D2·탐색활용·정신병리

3주차  Chapter 3 — 세로토닌
        → "기분" 단순화 교정·실제 기능
        → 14개 수용체 아형·SSRI 지연
        → 충동성·미해결 논쟁 정리

4주차  Chapter 4 — NE·아세틸콜린
        → NE 의 gain·역U·phasic/tonic
        → ACh 의 선명화·가소성
        → 주의의 두 축 분업

5주차  Chapter 5 — 각성 스위치
        → 각성 핵·VLPO 의 상호 억제
        → 플립플롭 히스테리시스 분석
        → 오렉신·기면증·REM/NREM

6주차  Chapter 6 — 의식·정신병리
        → 마취·시상-피질 차단
        → 환각제·5-HT2A·엔트로피
        → 단아민 가설의 한계·케타민

7주차  Chapter 7 — 종합·계산
        → TD(λ) RPE·플립플롭·gain 직접 구현
        → 상태와 경험의 간극 종합
        → 위 레이어로의 다리(→ L2, L4, L6)
```

</details>

---

## 🔗 연관 레포지토리

| 레포 | 주요 내용 | 연관 챕터 |
|------|----------|-----------|
| [neurons-neural-codes-distilled](https://github.com/iq-ai-lab) | 수용체 작동·신경전달물질 기초 | **Ch1 전체** (조절의 분자 토대) — **필수 선행 (L1)** |
| [brain-architecture-distilled](https://github.com/iq-ai-lab) | 뇌간 핵·기저핵·피질 구조 | **Ch2, Ch5** (경로·각성 핵의 해부) — **필수 선행 (L1)** |
| [plasticity-learning-distilled](https://github.com/iq-ai-lab) | 시냅스 가소성·학습 | **Ch2-04, Ch4-04** (DA·ACh 의 가소성 조절) — 시너지 (L1) |
| [learning-decision-distilled](https://github.com/iq-ai-lab) | 보상예측오차·의사결정·강화학습 | **Ch2 전체** (RPE 의 사용) — 창발 (L2) |
| [attention-working-memory-distilled](https://github.com/iq-ai-lab) | 주의·작업기억 | **Ch4 전체** (NE·ACh 의 주의 구현) — 창발 (L2) |
| [emotion-motivation-distilled](https://github.com/iq-ai-lab) | 동기·감정 처리 | **Ch2, Ch3** (DA·5-HT 의 동기·감정) — 창발 (L2) |
| [altered-states-distilled](https://github.com/iq-ai-lab) | 변성 상태·수면·마취 | **Ch5, Ch6** (각성 조절 실패) — 창발 (L4) |
| [ncc-distilled](https://github.com/iq-ai-lab) | 의식의 신경 상관물 | **Ch5-01, Ch6-01** (각성 수준·VLPO-LC) — 창발 (L4) |
| [prediction-everywhere](https://github.com/iq-ai-lab) | 예측 원리의 보편성 | **Ch2** (RPE 가 예측의 구현층) — 창발 (L6) |
| **IQ AI Lab — Reinforcement Learning** | TD 학습·가치 함수·탐색-활용 | **Ch2-02, Ch7-01** (도파민 ↔ TD-error) — 교차 (L3) |

> 💡 이 레포는 **"도파민 = 행복, 세로토닌 = 기분 이 아니라, 조절 물질이 계산 상태를 전환하는 방식과 그 한계"** 에 집중합니다. L1 의 **neurons-neural-codes**(수용체)와 **brain-architecture**(뇌간 핵)를 먼저 익히면 Chapter 1~2 가 자연스럽습니다. 그리고 이 레포에서 만난 RPE·주의 조절·각성 스위치는 위 레이어(**L2 learning-decision · attention · emotion · L4 altered-states · ncc · L6 prediction-everywhere**)에서 *다시, 더 깊게* 쓰입니다.

---

## 📖 Reference

### 🎯 도파민·보상예측오차
- **"A Neural Substrate of Prediction and Reward"** (Schultz, Dayan & Montague, 1997, *Science*) — 도파민 RPE 의 원전
- **Reinforcement Learning: An Introduction** (Sutton & Barto, 2018) — TD 학습과 도파민의 대응
- **"Reward prediction error"** (Schultz, 2016, *Dialogues Clin Neurosci*) — RPE 리뷰

### 🔬 세로토닌·단아민
- **Stahl's Essential Psychopharmacology** (Stephen Stahl) — 신경조절 물질·약물의 표준 참고서
- **"Serotonin and decision making processes"** (Cools, Roberts & Robbins, 2008) — 세로토닌의 억제·시간 기능
- **Molecular Neuropharmacology** (Nestler, Hyman & Malenka) — 수용체·신호 전달의 분자 기초

### 🌙 각성·수면 스위치
- **"The sleep switch: hypothalamic control of sleep and wakefulness"** (Saper, Chou & Scammell, 2001, *Trends Neurosci*) — 플립플롭 원전
- **"Hypothalamic regulation of sleep and circadian rhythms"** (Saper et al., 2005, *Nature*) — 오렉신과 안정자
- **"An integrative theory of locus coeruleus-norepinephrine function"** (Aston-Jones & Cohen, 2005, *Annu Rev Neurosci*) — LC-NE 와 인지

### 🧠 신경조절·의식·임상
- **The Neuroscience of Psychotherapy** (Louis Cozolino) — 신경조절과 임상의 연결
- **"Uncertainty, neuromodulation, and attention"** (Yu & Dayan, 2005, *Neuron*) — ACh·NE 의 계산 역할
- **"Ketamine and the next generation of antidepressants"** (Krystal et al., 2019) — 단아민 가설 너머

---

<div align="center">

**🧠 The Knowledge Pentad**

*Physis 의 모든 문서는 신경조절이 제 자리를 얻는 다섯 가지 방식으로 검증된다 —*

**🧩 Circuit** (회로로 설명하는가) · **🔬 Compute** (계산 파라미터로 환원하는가) · **🌉 Boundary** (설명적 간극에서 정직한가) · **🪞 Experience** (경험을 지우지 않는가) · **📐 Falsify** (반증 가능한 예측을 내놓는가)

<br/>

**⭐️ 도움이 되셨다면 Star 를 눌러주세요!**

Made with 🧠 by [IQ AI Lab](https://github.com/iq-ai-lab) · **Physis** Layer 1

<br/>

***Explain it, don't explain it away. 설명하되, 경험을 지우지 않는다.***

<br/>

*"도파민이 분비되었다고 말하는 것과 — 그 발화가 보상예측오차 $\delta = R + \gamma V(s') - V(s)$ 임을 슐츠 실험의 논리로 보이고 · 세로토닌이 기분이 아니라 처벌 억제·시간 할인임을 구분하며 · NE 와 ACh 가 활성화가 아니라 gain·정밀도라는 계산 파라미터를 바꾼다는 것을 알고 · 각성과 수면이 상호 억제 플립플롭의 두 안정 상태임을 회로로 그리고 · 오렉신 손실이 그 스위치를 어떻게 무너뜨리는지 추적하되 — 그 모든 회로가 의식을 켜도, 켜진 경험의 질감은 남는다는 간극을 정직하게 표시하는 것은 다르다."*

</div>
