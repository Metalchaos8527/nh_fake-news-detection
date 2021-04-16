# AI야, 진짜 뉴스를 찾아줘!
대회 url: https://dacon.io/competitions/official/235658/overview/description/   
**대회 규정상 원 데이터셋은 올리지 않았습니다**   

<br>

K-러닝 팀의 custom_bert_clf 개발기를 담은 파일들을 업로드 합니다   
구체적인 파일별 설명은 다음과 같습니다

1. [input_cleaning](https://github.com/Metalchaos8527/nh_fake-news-detection/blob/master/input_cleaning.ipynb) : 원자료 데이터를 처리할 방안을 고민한 파일입니다
2. [trial_model](https://github.com/Metalchaos8527/nh_fake-news-detection/blob/master/trial_model.ipynb) : 로지스틱 회귀, MLP를 이용하여 처음 학습을 시도한 내용을 담은 파일입니다
3. [BERT_model](https://github.com/Metalchaos8527/nh_fake-news-detection/blob/master/BERT_model.ipynb) : KoBERT모델을 이용하여 첫 BERT모델을 만들었습니다
4. [BERT_huggingface_model](https://github.com/Metalchaos8527/nh_fake-news-detection/blob/master/BERT_huggingface_model.ipynb) : Hugging Face라이브러리를 이용하여 보다 간결한 코드 구성 및 새로운 BERT모델을 만들었습니다
5. [predict_K-러닝](https://github.com/Metalchaos8527/nh_fake-news-detection/blob/master/Final_Submission/6.Code/predict_K-%EB%9F%AC%EB%8B%9D.ipynb) : DACON에 제출한 최종 학습 & 예측을 수행하는 코드입니다. 하이퍼파라미터 튜닝까지 적용된 최종 모델입니다

## 최종성적
Public: 24위  
Private: 33위  
