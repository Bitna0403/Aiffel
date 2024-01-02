
AIFFEL Campus Online 7th Code Peer Review Templete

코더 : 윤빛나

리뷰어 : 박 준


🔑 **PRT(Peer Review Template)**

- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 근거로 첨부
          
1번 루브릭 - accuracy가 기준 이상 높게 나왔는가?
![](https://github.com/currybab/first-repository/assets/7679722/0a43e2ef-aea5-4145-b655-f2da9643bdeb)
![](https://github.com/currybab/first-repository/assets/7679722/2397cc16-dab9-44af-802d-f3425dfa0463)
![](https://github.com/currybab/first-repository/assets/7679722/bb4b2141-5c40-42af-8eb4-3bb871bb41c6)
![](https://github.com/currybab/first-repository/assets/7679722/0a19d776-a228-42af-89e5-26fb37d4d3f5)
모든단어, 빈도수 상위 5000개, 10000개 단어에 대해서 8가지 머신러닝 기법을 적용하여 실험해주었습니다.
accuracy가 0.65 이상 최대 96 퍼센트로 충분히 높게 나왔습니다.

2번 루브릭 - F1 score가 기준 이상 높게 나왔는가?
![](https://github.com/currybab/first-repository/assets/7679722/0a19d776-a228-42af-89e5-26fb37d4d3f5)
![](https://github.com/currybab/first-repository/assets/7679722/99436241-b585-42a4-a2d0-edd7bfc02c4f)
f1 score도 대부분의 경우 높게 잘 나왔습니다.

3. 딥러닝 모델을 활용해 성능이 비교 및 확인되었는가?
![](https://github.com/currybab/first-repository/assets/7679722/ae16b908-3770-48d0-be1b-722cdddbed0a)
![](https://github.com/currybab/first-repository/assets/7679722/bef5c346-705c-4067-99bf-e0e78f79ba80)
위와 같이 딥러닝을 활용하여 성능비교를 실행하였습니다.

- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.

![](https://github.com/currybab/first-repository/assets/7679722/51d9f5ae-93c6-407c-9379-31d7e8c4f312)
![](https://github.com/currybab/first-repository/assets/7679722/8aff4bd3-b9b4-4ecd-8d49-b89618e4a3ae)
위와 같이 시각화나 데이터 전처리 부분에서 주석을 적절하게 달아주셨습니당
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인 또는
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
![](https://github.com/currybab/first-repository/assets/7679722/0fcee773-c0a1-4bbf-8b5d-6aa92fe94407)
위와같이 딥러닝  모델의 결과가 저조하게 나와서 vocab_size를 조정해가며 테스트해본 과정이 있습니다.
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 상세히 기록되어 있는지 확인
        - 딥러닝 모델의 경우,
        인풋이 들어가 최종적으로 아웃풋이 나오기까지의 전체 흐름을 도식화하여 
        모델 아키텍쳐에 대한 이해를 돕고 있는지 확인

![](https://github.com/currybab/first-repository/assets/7679722/cd4f5c0c-d05c-4dd1-98d9-ce160a15d61e")
회고 작성을 잘해주셨습니다.

- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 모듈화(함수화) 했는지
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.

![](https://github.com/currybab/first-repository/assets/7679722/51d9f5ae-93c6-407c-9379-31d7e8c4f312)
![](https://github.com/currybab/first-repository/assets/7679722/8aff4bd3-b9b4-4ecd-8d49-b89618e4a3ae)

전체적으로 코드가 간결하게 잘 작성되어있습니다
