# CM3191 유기 파트 폴더 안내 (AY2026/27 Sem 1)

마지막 정리: 2026-09-27

## 폴더 구성

| 폴더 | 실험 (목요일 Group A) | 들어 있는 .tex | 컴파일에 필요한 파일 |
|---|---|---|---|
| `1/` | Exp.1 Suzuki (10/1) | Bench Sheets, Concepts, Beginner Guide, **Report Draft**, Schlenk Line Prep | `common.tex` (Report Draft는 단독 컴파일) |
| `2/` | Exp.2 aldol–Diels–Alder (10/8) | **Report Draft** | `report_common.tex` |
| `3/` | Exp.3 NaBH4 환원 (10/22) | **Report Draft** | `report_common.tex` |
| `4/` | Exp.4 Grignard (10/15, 10/29) | **Report Draft** | `report_common.tex` |
| (이 폴더) | 전체 | Roadmap | `common.tex` |

- `1/_old/`: 수정 전 Bench Sheets와 Concepts (v1). 필요 없으면 지워도 됩니다.
- `Organic_Part_export/`: 강의·매뉴얼 원본 (새 과목 자료).
- `TalkFile_Expt-*.pdf`: 예전 유기 파트(Dr Zhang Sheng) 강의 자료. 실험은 바뀌었지만 크로마토그래피, Pd 커플링 메커니즘 부분은 새 실험에도 유효합니다.

## 컴파일

- 모든 문서는 **XeLaTeX**로 컴파일합니다 (한글: Noto Serif CJK KR).
- 공통 설정 파일(`common.tex`, `report_common.tex`)이 같은 폴더에 있어야 합니다.
- 보고서 초안의 첫 페이지는 한국어 작성 안내입니다. 제출할 때는 `\drafttrue`를 `\draftfalse`로 바꾸면 빠집니다.
- 회색 상자(`\res{}`, `\obs{}`, `\resp{}`)는 실험 후 본인 측정값으로 바꿔야 하는 자리입니다.

## PDF 관련 참고

- Roadmap과 Schlenk Line Prep은 .tex가 PDF보다 새 버전입니다 (확인 질문에 Schlenk 짝 작업 항목 추가, 문서 목록 갱신). 다시 컴파일하거나 채팅에서 받은 새 PDF로 교체하세요.
