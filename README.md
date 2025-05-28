# Finance Time Series Main Quest

| 구분           | 내용                                                                                                                   |
| ------------ | -------------------------------------------------------------------------------------------------------------------- |
| **프로젝트명**    | Finance Time Series Main Quest                                                                                       |
| **파일명**      | FinanceTimeSeries\_MainQuest.ipynb                                                                                   |
| **프로젝트 목적**  | 금융 시계열 데이터의 다양한 트렌드/볼륨 기반 지표를 계산하고, 피처 엔지니어링 및 머신러닝 모델 적용을 통해 예측 및 이상 탐지를 수행함.                                       |
| **데이터 설명**   | - 시계열 금융 데이터 (open, high, low, close, volume)<br>- 각종 기술적 지표(TA) 및 파생 피처 생성<br>- 가격·거래량 기반 EDA 및 파생변수 추출             |
| **주요 라이브러리** | pandas, numpy, matplotlib, scikit-learn, ta(technical analysis), xgboost, lightgbm 등                                 |
| **전처리 과정**   | - 결측치 처리 및 outlier 제거<br>- 로그 변환, 스케일링<br>- 지표별 결측/이상구간 처리                                                           |
| **피처 엔지니어링** | - 이동평균(MA), 볼린저 밴드, MACD, RSI, 모멘텀 등 트렌드/모멘텀 지표<br>- OBV, MFI, Chaikin Money Flow 등 거래량 지표<br>- 수익률, 변동성 등 다양한 파생 피처 |
| **모델링**      | - 랜덤포레스트, XGBoost, LightGBM 등 분류/회귀 모델 적용<br>- 하이퍼파라미터 튜닝<br>- 교차검증 및 성능평가(정확도, 정밀도, 재현율, ROC-AUC 등)                 |
| **주요 실험/분석** | - 각종 지표별 시각화<br>- 피처 중요도 분석<br>- confusion matrix, ROC curve 등 결과 시각화                                                |
| **프로젝트 실행법** | 1. Jupyter Notebook 실행<br>2. 필요한 패키지 설치<br>3. 데이터 파일 경로 확인 후, 각 셀을 순서대로 실행                                           |
| **폴더/파일 구조** | - `FinanceTimeSeries_MainQuest.ipynb`<br>- (필요시) `requirements.txt`, 데이터 파일 등                                        |
| **결과 및 시사점** | - 시계열 지표 및 피처 조합의 중요성 확인<br>- 데이터 전처리와 피처 엔지니어링이 모델 성능에 미치는 영향 체감<br>- 실험 반복을 통한 모델 개선 경험                            |
| **참고/문의**    | 추가 질문, 코드 활용 문의는 깃허브 이슈 또는 코멘트로 남겨주세요.                                                                               |
