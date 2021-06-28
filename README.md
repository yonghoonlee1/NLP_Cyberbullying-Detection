# Cyberbullying-Detection

Deep Learning을 활용한 사이버폭력 탐지 연구를 진행

* Dataset (Cyberbullying)
  - Formspring : cyberbully - 776, Non-Cyberbully - 11,997

* 모델 
  - BERT-CNN
  - BiLSTM : Transfer Learning 활용 (IMDB 감정분석 데이터셋으로 모델 학습 후, Formspring 데이터셋으로 추가 학습)

* Preprocessing 
  - 특수기호, URL 등 제거
  - 소문자로 변경

* Precision, Recall, F1-score 평가 지표 활용 : 데이터가 불균형적인 것 감안


  
