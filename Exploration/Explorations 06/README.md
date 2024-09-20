<img width="895" alt="image" src="https://github.com/user-attachments/assets/dd126e08-f1e8-41ed-b48c-f643038416fe"># AIFFEL Campus Online Code Peer Review Templete
- 코더 : **진수민**
- 리뷰어 : **양기택**


# PRT(Peer Review Template)
- [✅]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
          <img width="898" alt="image" src="https://github.com/user-attachments/assets/6b35362a-0485-4232-a163-a7ad2acc8d32">
          - > 원문과 예측의 비교와 그에 따른 분석을 잘 실어주었어요 :)  
            > 더불어서 추출적 요약 또한 성공적으로 구현하셨습니다!

    
- [✅]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="874" alt="image" src="https://github.com/user-attachments/assets/c6b780ae-16c7-4dd1-8cee-855838565dbb">
          - > 이해하기 어려운 정규표현식에 대해 자연어 주석이 달려있는 점, 읽기 좋습니다!

        
- [✅]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="895" alt="image" src="https://github.com/user-attachments/assets/70d3a0fe-0fd3-409b-a8a3-8e48b5ca6974">
          -> 상용 LLM과의 비교, 훌륭합니다!

        
- [✅]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        <img width="891" alt="image" src="https://github.com/user-attachments/assets/a6c42ccf-9c4f-40f5-be57-5535c70e34ff">
        - > 회고를 정말 자세하게 잘 적어주셨어요!
        
- [✅]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="845" alt="image" src="https://github.com/user-attachments/assets/7fdc869c-9f06-4f64-95bf-e5dbb5d67f5c">
          - > 함수로 잘 정의되어 있어요!



# 회고(참고 링크 및 코드 개선)
```
모델 훈련에서 우리 조는 전반적으로 validation loss가 2 이상으로 나왔으나, 여기서는 1.5로 상당히 작게 나와서 어떤 차이가 있는지 궁금했다.
노드의 코드와는 큰 차이가 없으나, headline 부분에서도 불용어 제거 처리를 했다고 하여, 한 번 시도하고 비교해봐야겠다느 생각을 했다.
```
