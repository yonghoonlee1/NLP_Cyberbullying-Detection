# Cyberbullying-Detection

Deep Learning을 활용한 사이버폭력 탐지에 대한 연구를 진행

* Dataset (Cyberbullying)
  - Formspring : cyberbully - 776, Non-Cyberbully - 11,997
  - Twitter racism : cyberbully - 1890, Non-Cyberbully - 10,752
  - Twitter sexism : cyberbully - 3021, Non-Cyberbully - 10,752

* 모델 : Glove + CNN-BiLSTM
  - Glove(Word Embedding) : 50차원의 벡터 활용
  - CNN-BiLSTM : Convolutional Neural Networks + Bidirectional LSTM

* Preprocessing 
  - 특수기호, URL 등 제거
  - 소문자로 변경
  - lemmatize

* 5-fold cross validation 활용

* Precision, Recall, F1-score 평가 지표 활용 : 데이터가 불균형적인 것 감안


  
