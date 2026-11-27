# AIFFEL Quest 저장소

AIFFEL Campus Online 과정에서 진행한 코딩 퀘스트와 프로젝트를 정리한 저장소입니다.
카테고리별 폴더 아래에 퀘스트 폴더가 있고, 각 폴더에는 퀘스트 코드(.ipynb)와 피어 리뷰 템플릿(PRT)이 들어 있습니다.

## 폴더 구조

| 폴더 | 내용 | 퀘스트 폴더 |
|---|---|---|
| `Python/` | 파이썬 코딩 퀘스트 | Py01 ~ Py05 |
| `Computer_Vision/` | 컴퓨터 비전 | CV01 ~ CV03 |
| `Data_Analysis/` | 데이터 분석 | DA01 ~ DA02 |
| `NLP/` | 자연어 처리 | NLP01 ~ NLP05 |
| `LLM_Application/` | LLM 응용 | LLM01 ~ LLM05 |
| `MLOps/` | MLOps | MLOps01 ~ MLOps07 |
| `Main_Quest/` | 메인 퀘스트 | Quest01 ~ Quest05 |
| `Deployment/` | 배포 자료 | Contents, Final_Code |

각 퀘스트 폴더의 `README.md`는 [피어 리뷰 템플릿(PRT)](#피어-리뷰-방법)입니다.

## 진행 현황

| 상태 | 퀘스트 | 노트북 |
|---|---|---|
| ✅ 완료 | 파이썬 퀘스트 01 — 은행계좌 만들기 | `Python/Py05/Quest01_Bank_Account.ipynb` |
| ✅ 완료 | 파이썬 퀘스트 02 — 다각형(사각형) 넓이 구하기 | `Python/Py05/Quest02_Polygon_Area.ipynb` |
| ✅ 완료 | 파이썬 퀘스트 03 — 키오스크 만들기 | `Python/Py05/Quest03_Kiosk.ipynb` |
| ⬜ 예정 | 컴퓨터 비전, 데이터 분석, NLP, LLM, MLOps 퀘스트 | 진행하면서 추가 |

모든 노트북은 실행 결과(output)가 포함되어 있어 열어서 바로 확인할 수 있습니다.

## 피어 리뷰 방법

1. 리뷰할 퀘스트 폴더의 `README.md`(PRT)를 연다.
2. **코더 / 리뷰어** 이름을 채운다.
3. 5개 항목의 체크박스를 확인하며, 근거가 되는 부분은 **캡처 이미지로 첨부**한다.
4. 마지막 회고(참고 링크 및 코드 개선)에 리뷰어 의견을 남긴다.

## 실행 방법

```bash
pip install jupyter
jupyter notebook
```

노트북(`.ipynb`)을 열어 위에서부터 순서대로 실행하면 됩니다.
`Quest03_Kiosk.ipynb`의 시연 셀은 `input()`을 미리 준비한 답변으로 대체해 자동 실행되며, 그 아래 안내대로 답변 리스트를 바꾸면 원하는 주문 시나리오를 재현할 수 있습니다.
