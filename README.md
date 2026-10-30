# Hotel Booking Cancellation Analysis

> **Bootcamp Mission 02** | Data Analysis

## 미션 소개
호텔 예약 데이터에서 예약 취소에 영향을 주는 요인을 탐색하고, 취소율을 낮추기 위한 분석 관점을 정리한 데이터 분석 미션입니다. 결측치와 범주형 데이터를 점검한 뒤 시각화를 통해 예약 패턴을 해석합니다.

## 구현 목표
- 호텔 예약 데이터의 구조와 품질을 점검한다.
- 예약 취소와 주요 변수의 관계를 시각화한다.
- 분석 결과를 운영 관점의 인사이트로 정리한다.

## 주요 구현 내용
- 기초 통계와 결측치 확인
- 예약 취소율 비교 시각화
- 고객 및 예약 조건별 패턴 해석

## 사용 기술
- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

## 실행 방법
```bash
pip install -r requirements.txt
jupyter notebook notebooks/mission02.ipynb
```

> 데이터셋 또는 사전학습 모델이 외부에서 제공되는 경우, 실행 전에 노트북 또는 코드의 데이터 로드 설정을 확인해야 합니다.

## 폴더 구조
```text
notebooks/
  mission02.ipynb
README.md
requirements.txt
.gitignore
```

## 학습 내용
- 분석 전 데이터 정의와 결측치 처리 기준을 먼저 확인하는 습관
- 시각화 결과를 단순 수치가 아니라 비즈니스 질문과 연결하는 방법

## 트러블슈팅 및 재현 시 참고 사항
외부 데이터셋의 경로나 다운로드 조건은 노트북의 데이터 로드 셀을 확인해야 합니다.

## 결과 확인
분석 과정과 시각화 결과는 노트북 실행 출력에서 확인할 수 있습니다.

## 포트폴리오 관점
이 저장소는 **Data Analysis** 역량을 학습·실험한 결과물입니다. 구현 범위와 실행 조건은 코드 및 노트북을 기준으로 확인할 수 있습니다.