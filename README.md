# 🐸캐굴캐굴🐸

## AIS7 수료 이후 스터디 

### 학습 목록
1. 1주차 (23/02/07) : [goodbooks-10k](https://www.kaggle.com/datasets/zygmunt/goodbooks-10k/code)
   - 필사 노트북 [🔴Netflix Vs Books-Recommender, Analysis, EDA](https://www.kaggle.com/code/niharika41298/netflix-vs-books-recommender-analysis-eda/notebook)
   - 학습 내용
     - error_bad_lines=False → 23/04/14 FutureWarning : on_bad_lines="skip"으로 수정
     - 23/04/14 FutureWarning : distplot → displot으로 수정
     - .drop_duplicates(subset=[], keep=False)
     - 추천 시스템
2. 2주차 (23/02/12) : []
     - 필사 노트북 [Complete EDA & Baseline model [0.708 LB] 🐦 🐦]()
     - 학습 내용
       - 정규표현식
       - 자연어 처리에서의 EDA (제목 길이 분포, 토큰 수 분포, 토큰별 길이 분포, 워드 클라우드)
       - PorterStemmer()
3. 3주차 (23/02/19) :
   - 필사 노트북 [House Price Calculation methods for beginners]
   - 학습 내용
     - 상관관계를 위한 히트맵을 그릴 때, 변수가 너무 많다면 필요한 변수를 뽑아서(ex. 상관도 절대값이 0.5 이상) 다시 히트맵을 그림
     - 상관도를 sort_values를 통해 수치를 정렬해서 높은 상관관계를 찾아보기
     - 왜도와 첨도 : .skew() 또는 .kurtosis() => kdeplot / scipy.stats에서 norm, skew를 import 해서 distplot으로 시각화
     - 이산화
     - 다항식 전개
  1. 4주차 (23/02/26) : E-Commerce Data Analysis(CRM)
     - 필사 노트북 [[KOR] E-Commerce Data: 2. RFM Analysis](https://www.kaggle.com/code/blanik/kor-e-commerce-data-2-rfm-analysis/notebook#Segmentation-Method-2:-Quartile-Sum) & 조은님 강의 필사
     - 학습 내용
       - 인코딩 오류 : encoding = "ISO-8859-1" 추가
       - RFM segment
  2. 5주차 (23/03/06) : [Melbourne Housing Market]
     - 필사 노트북 [Melbourne Housing Market EDA and Regression](https://www.kaggle.com/code/stephaniestallworth/melbourne-housing-market-eda-and-regression)
     - 학습 내용
       - np.where(조건식, True일 때 반환값, False일 때 반환값)
       - missing data 제거 방법
       - zero-lot-line
       - R2 Score 계산 방법 2가지
  3. 6주차 (23/03/13) : [Airbnb New User Bookings]
     - 필사 노트북 [Airbnb New User Bookings](https://www.kaggle.com/code/rounakbanik/airbnb-new-user-bookings)
     - 학습 내용
       - 결측치 확인 방법 : .any(), .all()
       - categorical binary variable
       - 추론 통계(Inferential Statistics)

---

## [AIS7] kaggul_kaggul_study
멋쟁이 사자처럼 AI School 7기,
캐글 노트북 필사 스터디 

### 학습 목록
1. 1주차 (22/11/07) CLF : 캐글 분류과제 노트북 필사
   
   - 추천시스템 [Airbnb New User Bookings](https://www.kaggle.com/competitions/airbnb-recruiting-new-user-bookings) 로 대체
   - 학습 내용
     - ing


2. 2주차 (22/11/15) REG : 캐글 회귀과제 노트북 필사
   - [Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance?datasetId=13720&sortBy=voteCount)
   - 필사 노트북 [EDA + Regression](https://www.kaggle.com/code/hely333/eda-regression)

   - 학습 내용 
3. 3주차 (22/11/22) DNN : MNIST 숫자 & 패션 데이터 이미지 분류 노트북 필사
   - [MNIST 숫자 분류](https://www.tensorflow.org/tutorials/quickstart/beginner)
   - [MNIST 패션 분류](https://www.tensorflow.org/tutorials/keras/classification)
4. 4주차 (22/11/29) DNN : 3주차 DNN
5. 5주차 (22/12/07) CNN : CIFAR10 Dataset Classification LeNet-5 Model
   - [합성곱 신경망](https://www.tensorflow.org/tutorials/images/cnn?hl=ko)
   - [이미지 분류](https://www.tensorflow.org/tutorials/images/classification?hl=ko)
6. 6주차 (22/12/13) RNN : 
   -  [Text classification with an RNN](https://github.com/tensorflow/text/blob/master/docs/tutorials/text_classification_rnn.ipynb)
7. 7주차 (22/12/20) 추천시스템 : 
   - [Netflix Visualizations, Recommendation, EDA🍿](https://www.kaggle.com/code/niharika41298/netflix-visualizations-recommendation-eda#Top-Duration)
   - [코사인 유사도](https://wikidocs.net/24603)

---