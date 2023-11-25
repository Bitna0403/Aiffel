
AIFFEL Campus Online 7th Code Peer Review Templete

코더 : 윤빛나

리뷰어 : 옥창우

🔑 **PRT(Peer Review Template)**

# 1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?
>- 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
>- 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 퀘스트 문제 요구조건 등을 지칭
>    - 해당 조건을 만족하는 부분의 코드 및 결과물을 근거로 첨부
---
     
|평가문항|상세기준|
|---|---|
|1. 다양한 방법으로 Text Classification 태스크를 성공적으로 구현하였다.	|3가지 이상의 모델이 성공적으로 시도됨|
|2. gensim을 활용하여 자체학습된 혹은 사전학습된 임베딩 레이어를 분석하였다.|	gensim의 유사단어 찾기를 활용하여 자체학습한 임베딩과 사전학습 임베딩을 비교 분석함|
|3. 한국어 Word2Vec을 활용하여 가시적인 성능향상을 달성했다.|	네이버 영화리뷰 데이터 감성분석 정확도를 85% 이상 달성함|


## 루브릭 1. 다양한 방법으로 Text Classification 태스크를 성공적으로 구현하였다.
- 3가지 이상의 모델이 성공적으로 시도됨: `Simple LSTM`, `Bidirectional LSTM`, `1D-CNN`
  
(1) SimpleLSTM<br>
    
<img width="821" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/1ae21cfb-9303-4962-a5d4-c3d3034b5946"><br>
   
(2) Bidirectional LSTM<br>
    
<img width="825" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/5c0c8d4d-0953-4f82-af87-31b7e10b7dbb"><br>
   
(3) 1D-CNN<br>
    
<img width="827" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/0b7778ba-f549-4d99-acb3-7dafe331341c"><br>


## 루브릭 2. gensim을 활용하여 자체학습된 혹은 사전학습된 임베딩 레이어를 분석하였다.  
- gensim의 유사단어 찾기를 활용하여 자체학습한 임베딩과 사전학습 임베딩을 비교 분석함<br>

<img width="608" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/1a97751b-9452-4d50-b46b-a32b6840c709">

    
## 루브릭 3. 한국어 Word2Vec을 활용하여 가시적인 성능향상을 달성했다. 
- 네이버 영화리뷰 데이터 감성분석 정확도를 85% 이상 달성함<br>

(1) 임베딩 차이 비교<br>

<img width="795" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/378be492-3151-483c-a3d5-af519370041a"><br>

(2) accuracy: 0.8906<br>

<img width="820" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/9c6b229c-ff93-43b8-aa3c-3c64e3880107"><br>


# 2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?
>- 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
>- 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
>- 주석을 보고 코드 이해가 잘 되었는지 확인
>    - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
---

- 제일 복잡할 수 있는 전처리 loader함수 부분에서 주석을 블록별로 간단하게 명시<br>
  
<img width="683" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/29a2641c-3834-4274-92e3-f3d7ed94d042"><br>


# 3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나”, ”새로운 시도 또는 추가 실험을 수행”해봤나요?
>- 문제 원인 및 해결 과정을 잘 기록하였는지 확인 또는
>- 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 실험이 기록되어 있는지 확인
>    - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
---

<img width="516" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/b94a579f-ba8a-4012-a9d0-4060e6645c5e">


# 4. 회고를 잘 작성했나요?
>- 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해<br>
    배운점과 아쉬운점, 느낀점 등이 상세히 기록되어 있는지 확인
>    - 딥러닝 모델의 경우,<br>
        인풋이 들어가 최종적으로 아웃풋이 나오기까지의 전체 흐름을 도식화하여<br>
        모델 아키텍쳐에 대한 이해를 돕고 있는지 확인
---

<img width="717" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/dd6819d6-889a-4d4b-a7d0-742750382b0e"><br>

<img width="492" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/81178e6e-19d4-4921-87bc-9510de629f98">


# 5. 코드가 간결하고 효율적인가요?
>- 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
>- 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 모듈화(함수화) 했는지
>    - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
---

- 모든 부분에서 간결하고 기능별로 깔끔하게 과정을 보여줌

(1) 데이터 전처리<br>

<img width="683" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/ead4270d-e4a8-4d25-9eb2-6d417611af24"><br>

(2) 모델 building<br>

<img width="734" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/91de479e-14f2-434c-aa5c-dedff8eea57d"><br>

(3) 분석, 시각화<br>

<img width="602" alt="image" src="https://github.com/Bitna0403/Aiffel/assets/124979889/de9fc045-d7f5-48a2-9322-e0543fcb8d0f"><br>


