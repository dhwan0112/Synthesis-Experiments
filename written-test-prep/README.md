# CM3191 Written Test 대비 노트

AY2026/27 Sem 1, CM3191 Chemical Synthesis Experiments (유기 + 무기). 이 폴더의 노트는 저장소에 올라 있는 매뉴얼, 강의 자료, 보고서 초안을 근거로 작성했습니다.

## 1. 시험에 대해 확인된 것과 확인되지 않은 것

| 항목 | 내용 | 근거 |
|---|---|---|
| 형식 | Closed-book written test. 유기와 무기를 함께 봅니다 | [L-무기 s20] (작년 자료) |
| 범위 | 실험의 이론, 실습, 안전 측면. 실습, 강의, 강의노트에서 다룬 내용 | [L-무기 s20] (작년 자료) |
| 일정 | 올해 유기 파트 일정표에 "13주차 Written test"로 표시 | `organic/Organic_Part_export/CM3291 Organic Lecture and Lab schedule.pdf` |
| 작년 사례 | 13주차 월요일, 강의 시간, LT26, 무기 파트 15% | [L-무기 s15, s19, s20] |
| 선배 후기 (비공식) | 아래 2절 | 카카오톡 캡처 (이름 생략) |
| **확인되지 않음** | 올해의 날짜, 장소, 시간, 문항 수, 배점, 출제 교수. 올해 공지(Canvas)를 꼭 확인하세요 | - |

주의: 작년(AY24/25) 강의노트의 날짜와 비율은 올해와 다를 수 있습니다. 시험 범위와 형식도 올해 공지가 우선입니다.

## 2. 선배 후기 정리 (비공식, 연도 미상)

사진 속 대화에서 읽을 수 있는 내용입니다. 해석이 필요한 부분은 따로 적었습니다.

- 실험 방법과 프로세스를 잘 외워 둘 것.
- "뭐가 틀렸는지 고치기" 유형이 나올 수 있으니 고칠 줄 알아야 함. (틀린 절차나 서술을 주고 바로잡게 하는 문제로 해석했습니다.)
- 기본적인 안전 수칙이 나옴.
- "crystal structure인가 뭔가"를 문제로 냄. 꽤 어려웠다고 함.
- 대화에 "에디스는"이라는 말이 두 번 나옵니다. 무기 파트 담당 교수의 이름이 Dr. Edith Chan이므로([L-무기 s3]), 무기 파트 출제 이야기로 읽는 것이 자연스럽습니다. 다만 대화가 중간에서 끊겨 있어 확실하지 않습니다. 그래서 crystal structure는 무기와 유기 양쪽 모두 대비해 두었습니다. 유기 실험 2도 X선 결정구조를 해석하는 단계가 있습니다([M-유기 p12]).

## 3. 출처 표기 규칙

| 표기 | 뜻 |
|---|---|
| [M-무기 pN] | 무기 실험 매뉴얼(AY26/27) N쪽. `inorganic/AY2627sem1_CM3191_lab manuals for INORGANIC experiments.pdf` |
| [M-유기 pN] | 유기 실험 매뉴얼(AY26/27) N쪽. `organic/Organic_Part_export/CM3191 Lab manual AY2627 Sep 2026.pdf` |
| [L-무기 sN] | 무기 강의노트 슬라이드 N번 (**AY24/25, 작년 자료**). `inorganic/TalkFile_*.pdf`, `inorganic/AY2425sem1_*.pdf` |
| [L1], [L2] | 유기 강의 슬라이드(Suzuki, Aldol/Diels-Alder). `organic/Organic_Part_export/` |
| [SN pN] | `Undergraduate Safety Note.pdf` N쪽 |
| [초안] | 저장소의 유기 보고서 초안(`organic/N/...Report Draft.tex`)과 그 참고문헌 |
| [G] | 일반 화학 지식. 제공된 자료에는 없으므로 시험 전에 교재나 강의로 확인하세요 |
| [추론] | 자료가 직접 말하지 않아 해석해서 적은 부분 |

수치와 절차는 모두 AY26/27 매뉴얼 기준입니다. 작년 강의노트와 다른 점은 해당 위치에 "버전 차이"로 표시했습니다.

## 4. 폴더 구성과 학습 순서

```
written-test-prep/
  README.md                       이 문서
  safety.md                       안전 수칙 + 실험별 위험물/폐기물 (유기·무기 공통, 반드시 먼저)
  inorganic/
    01_exp1_ruthenium.md           무기 실험 1: Ru 촉매 합성과 촉매 산화
    02_exp2_ferrocene.md           무기 실험 2: 페로센 합성과 분석
    03_theory_and_analysis.md      ESI-MS, NMR, 자기감수율, UV-vis, 전자 계수(CBC), TON/TOF
    04_crystal_structure.md        결정구조 문제 대비 (RuCl2(PPh3)3, 페로센)
    05_practice.md                 절차 암기 확인, 틀린 곳 고치기, 계산, 개념 문제 (정답 포함)
  organic/
    01_exp1_suzuki.md              유기 실험 1: Suzuki-Miyaura 커플링
    02_exp2_aldol_DA.md            유기 실험 2: Aldol 축합 + Diels-Alder (X선 구조 해석 포함)
    03_exp3_reduction.md           유기 실험 3: 4-tert-butylcyclohexanone의 NaBH4 환원
    04_exp4_grignard.md            유기 실험 4: Grignard (linalool), Schlenk line, 컬럼
    05_techniques.md               재결정, 여과, 추출, TLC, 컬럼, 회전증발, NMR 시료 준비
    06_practice.md                 절차 암기 확인, 틀린 곳 고치기, 계산, 개념 문제 (정답 포함)
```

시험 유형별로 볼 곳은 다음과 같습니다.

| 유형 | 먼저 볼 문서 |
|---|---|
| 절차와 프로세스 암기 | 각 실험 문서의 "절차 요약"과 "외울 숫자" 표 |
| 틀린 곳 고치기 | `05_practice.md`(무기), `06_practice.md`(유기), 각 실험 문서의 "자주 틀리는 곳" |
| 안전 수칙 | `safety.md` |
| crystal structure | `inorganic/04_crystal_structure.md`, `organic/02_exp2_aldol_DA.md`의 "X선 구조" 절 |
| 계산 | 각 실험 문서의 "계산" 절 |

## 5. 사용할 때 주의할 점

1. 이 노트는 자료에서 읽은 내용을 정리한 것입니다. 정답을 보장하지 않으며, 실제 시험의 출제 방향은 확인되지 않았습니다.
2. [G]와 [추론] 표시가 붙은 부분은 시험 전에 강의나 교재로 한 번 더 확인하세요.
3. 실제 수행한 실험의 관찰과 측정값(수율, 스펙트럼 등)은 이 노트에 없습니다. 본인의 datasheet와 보고서를 함께 보세요.
4. 보고서 초안이 있는 유기 실험 1~4는 `organic/` 폴더의 `.tex`와 `.pdf`에 더 자세한 설명과 참고문헌이 있습니다. 이 노트는 그 내용을 시험용으로 줄여 놓았습니다.
