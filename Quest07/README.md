
AIFFEL Campus Online 7th Code Peer Review Templete

코더 : 윤빛나

리뷰어 : 이승제

🔑 **PRT(Peer Review Template)**

- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    1. 데이터 분석 과정 및 한 가지 이상의 augmentation을 포함한 데이터셋 구축 과정이 체계적으로 제시되었다.  
 
        ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/17662606-fb0f-4115-a812-01ba51b84598)

        **-> augmentation을 포함한 데이터셋 구축 과정이 체계적으로 작성되었다.**

       
    2. U-Net generator, discriminator 모델 구현이 완료되어 train_step의 output을 확인하고 개선하였다.  

        ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/f0deba5a-444e-4d43-aa7a-b9ece5885638)
     
        ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/bdf4d415-f223-4f0b-859a-3aef26213f96)
        
        **-> U-Net generator, discriminator 모델을 구현하여 output 성능이 개선하였다.**

       
    3. 10 epoch 이상의 학습을 진행한 후 최종 테스트 결과에서 진행한 epoch 수에 걸맞은 정도의 품질을 확인하였다.  
     
        ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/19bf813e-a2b6-4fa2-8fa1-b4e83382ba06)


<br/>

---

<br/>

- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

    ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/eca48d6d-8556-40a1-abdc-5bbf598ed3b1)
  
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인  
        
        **-> augmentation 함수를 작성하고 주석이 잘 달려있다.**  


    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.  
        **-> 해당 코드는 입력이미지를 회전, 크롭등 다양한 방법으로 이미지 케이스를 늘리는 방법.**
    
    
    - 주석을 보고 코드 이해가 잘 되었는지 확인  
     
        ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/3eea4c2e-4fe5-4531-b6f7-8499f0f556d7)

        **-> 위의 이미지처럼 동작하는 이유를 주석을 보고 잘 이해할 수 있었다.**

<br/>

---

<br/>
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나”, ”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인  
        ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/5a09636b-899b-48e6-b955-fbca98148297)

        **-> 문제 원인과 해결을 잘 기록하였다.**


    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 실험이 기록되어 있는지 확인  
        ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/33735974-3fbe-426f-bf75-fdc7411251d9)
  
        
        **-> 채도와 색도를 조절하는 새로운 시도가 있었다.**

<br/>

---

<br/>
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해 배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인  
        ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/b5cc5229-cebb-4bd3-bbc6-6c0f72beb45f)

        **-> 프로젝트를 진행하면서 아쉬운 점과 느낀점이 기록이 되어있다.**


    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인  
        ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/450b0496-23a1-4b53-8a5c-d8f500ea115c)
        
        **-> 이미지 처리가 진행되면서 변화하는 loss 과정을 출력하여 이해를 돕고 있다.**

<br/>

---

<br/>
        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인  
        
        **-> class명은 CamelCase, 함수명은 소문자로 구성되어 준수하였다.**


    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지  
        ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/3b6d0d79-5099-43e5-9789-1db8ff36a0dd)
  
        **-> augmentation 부분을 함수화 시켰다.**


    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지  
        ![image](https://github.com/happybin2013/AIFFEL_Queust_Bitna0403/assets/85716670/8f8dc363-771d-4aa7-ac79-01dfde03ef6e)
  
        **-> load_img 함수는 자주 사용된 코드로 중복을 최소화 했다.**
