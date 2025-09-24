# 딥러닝을 이용한 자연어 처리 입문

`2장, 7장, 8장`을 중심으로 공부하되, 다른 장도 읽어보면서 중요한 것들 위주 정리

> LLM 을 큰 주제로 본다면 배워야할 것 : 이론적 위주
>
> - 트랜스포머 (Transformer)
> - BERT, GPT, BART, T5, GPT-3
> - PEFT(Parameter-Efficient Fine-Tuning), LLama



### 1장. 자연어 처리 (natural language processing)

**자연어(natural language)** : 일상 생활에서 사용하는 언어

**자연어 처리** : 자연어의 의미를 분석하여 컴퓨터가 처리할 수 있도록 하는 일 



- 필요 프레임워크 , 라이브러리 

> 필요한 패키지 
>
> - 코랩 (Colab) or Anaconda : 이미 설치 완료
> - Tensorflow : 구글에서 공개한 머신 러닝 오픈소스 라이브러리 
> - Keras : 딥러닝 프레임워크인 텐서플로우에 API 제공
> - Gensim : 머신러닝을 사용해 토픽 모델링과 자연어 처리를 수행을 도와주는 오픈 소스 라이브러리
> - Scikit-learn : 파이썬 머신러닝 라이브러리
> - KoNLPy : 한국어 자연어 처리를 위한 형태소 분석기 패키지
