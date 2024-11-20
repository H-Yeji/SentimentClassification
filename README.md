## [텍스트 마이닝] 감정 분류 
<img src="https://github.com/user-attachments/assets/854a2d45-4a1b-49b3-9f2e-f93bc2de34de">
<br>

### ✏️ Kaggle 경진대회
https://www.kaggle.com/datasets/pashupatigupta/emotion-detection-from-text
<br><br><br>

<hr>
<br>

### 📂 Data 
<img src="https://github.com/user-attachments/assets/880d1477-9831-47f0-bdbb-47d2415e5515" width=700><br>
트위터에서 트윗을 작성한 사람이 주석의 형태로 작성해둔 emotion과 text로 이루어진 데이터
<br><br><br>

<hr>
<br>

### ⚙️ Task 
주어진 text를 학습시켜, 13가지의 **emotion**(happiness, love, fun, relief, enthusiasm, worry, sadness, hate, anger, neutral, empty, boredom, surprise)으로 감정 분류하기 
<br><br><br>

<hr>
<br>

### 📈 과정 
(1) EDA & 데이터 전처리 - 불필요한 피처 제거, 텍스트 전처리, 인코딩<br>
(2) DistilBert 모델을 활용한 훈련학습 - tokenization, padding, masking <br>
(3) LogisticRegression 모델을 활용한 예측 <br>
(4) 성능 향상 - 13가지의 감정 종류를 5개로 축소시켜서 진행 
<br><br><br>

<hr>
<br>

### 💡 결과 
<img src="https://github.com/user-attachments/assets/e5a28480-8017-48de-8591-f3e37d88ab64" width=700><br>
정확도 0.322 ➡️ 0.542로 향상 
