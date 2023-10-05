## 자연어 처리 Task 중 문서 분류(Text Classification) 에 대한 내용입니다.
- 실습 프로세스
    1. IMDB 영화 평점 데이터 감정 분류 0 또는 1
    2. 문서 전처리 : 특수문자 제거, 공백 제거, 불용어(stopword) 제거
    3. 문서 벡터화, 임베딩 → 각각에 해당하는 params 정의 → 객체 생성 및 훈련 (fit_transform)
        1. TF-IDF
        2. ConterVectorizer
        3. word2vec
    4. 벡터화 된 훈련 데이터 모델에 학습
        1. 로지스틱 회귀
        2. 랜덤포레스트
        3. 순환신경망(RNN) 분류모델
        4. 합성곱신경망(CNN) 분류모델
