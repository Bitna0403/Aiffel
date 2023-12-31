
AIFFEL Campus Online 7th Code Peer Review Templete

코더 : 윤빛나

리뷰어 : 방은송


루브릭 아래의 기준을 바탕으로 프로젝트를 평가합니다. 평가문항 상세기준

SentencePiece를 이용하여 모델을 만들기까지의 과정이 정상적으로 진행되었는가? 코퍼스 분석, 전처리, SentencePiece 적용, 토크나이저 구현 및 동작이 빠짐없이 진행되었는가?
SentencePiece를 통해 만든 Tokenizer가 자연어처리 모델과 결합하여 동작하는가? SentencePiece 토크나이저가 적용된 Text Classifier 모델이 정상적으로 수렴하여 80% 이상의 test accuracy가 확인되었다.
SentencePiece의 성능을 다각도로 비교분석하였는가? SentencePiece 토크나이저를 활용했을 때의 성능을 다른 토크나이저 혹은 SentencePiece의 다른 옵션의 경우와 비교하여 분석을 체계적으로 진행하였다.


🔑 **PRT(Peer Review Template)**

- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 근거로 첨부
    
    ![image](https://github.com/Bitna0403/Aiffel/assets/134351442/9ecb2564-ba70-4685-8c0e-55c7b72f109a)
    ![image](https://github.com/Bitna0403/Aiffel/assets/134351442/ca096f8e-731a-4735-866d-93301f2f1150)

    **Unigram과 BPE 비교**

    ![image](https://github.com/Bitna0403/Aiffel/assets/134351442/6f7b16a3-d401-4afa-9972-8c3ac3200f23)
    ![image](https://github.com/Bitna0403/Aiffel/assets/134351442/7abd1ac7-a06a-4dc1-bfd0-04977f10a70a)


    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
    **주석을 달아주었습니다**

    ![image](https://github.com/Bitna0403/Aiffel/assets/134351442/33f0ddfc-f24a-4598-b097-2a5f00386d65)

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인 또는
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
    **BPE 모델 타입을 변경하여 추가 실험을 진행했습니다**

    ![image](https://github.com/Bitna0403/Aiffel/assets/134351442/23a84588-8b11-48c2-bfa5-9a1b1eb68e36)

    
- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 상세히 기록되어 있는지 확인
        - 딥러닝 모델의 경우,
        인풋이 들어가 최종적으로 아웃풋이 나오기까지의 전체 흐름을 도식화하여 
        모델 아키텍쳐에 대한 이해를 돕고 있는지 확인
    **회고를 작성했습니다**

    ![image](https://github.com/Bitna0403/Aiffel/assets/134351442/c3c68a70-d1f6-4be1-be37-2306e71f5753)


- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 모듈화(함수화) 했는지
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
    **함수화를 했습니다**

    ![image](https://github.com/Bitna0403/Aiffel/assets/134351442/5d5a6f02-0a53-4d6a-a3db-4a79fe547988)
    ![image](https://github.com/Bitna0403/Aiffel/assets/134351442/234c72a5-5d52-422e-96c5-604755b9e581)



