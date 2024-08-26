<img width="168" alt="캡쳐1" src="https://github.com/user-attachments/assets/159719a2-248e-4fe8-b560-a9dc0e565536"># AIFFEL Campus Online Code Peer Review Templete
- 코더 : 코더의 이름을 작성하세요.
- 리뷰어 : 리뷰어의 이름을 작성하세요.


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부

    - Project01에서는 MSE를 2771을 달성함
   <img width="187" alt="image" src="https://github.com/user-attachments/assets/043c6b10-4a56-42c4-b42d-91bf041b9909">

    - Project02에서는 RMSE를 달성함
    - <img width="168" alt="캡쳐1" src="https://github.com/user-attachments/assets/c0506515-00e2-486d-9b41-fb20be87b284">

- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - <img width="274" alt="image" src="https://github.com/user-attachments/assets/03264c24-98c0-454a-9faf-ef3e80b3b432">  

    - 해당 코드블럭은 Project01에서 model을 설계하는 부분으로 핵심적이라고 생각
    - 해당 코드 블럭에 doc string/annotation이 **달려있지않음**
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 **기술하지 않음**
    - 
    - 주석이 **달려있지 않음**
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 에러가 난 부분에 대해서 시간이 촉박해서 디버깅을 진행하지 않음  
      
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [X]  **4. 회고를 잘 작성했나요?**
    - **회고를 작성하지 않음**
      
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
 
      
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
    - <img width="302" alt="image" src="https://github.com/user-attachments/assets/99ab5a25-cb06-46a4-a170-57a6d015432f">


# 회고(참고 링크 및 코드 개선)

회고를 진행할때 github에서 진행하면 편하다는걸 알려주셔서 감사합니다

처음 프로젝트를 진행하다보니 각 코드에 주석을 달아야 하는점  
회고를 작성해야하는 점, 프로젝트 전체 흐름을 작성해야하는점을  
몰랐기때문에 적지않은 부분은 다음번에 잘 적으실거라고 생각합니다!


### 개선한 코드

<img width="425" alt="image" src="https://github.com/user-attachments/assets/9e8cea2c-7576-464a-b13d-be096a812e94">

위 이미지에서 df['datetime'] 컬럼을 'datetime' 형식으로 바꿔주지않으니 제 쪽에서 오류가났습니다

```python
df['datetime'] = pd.to_datetime(df['datetime'])
```
이 한줄을 위에 추가해줬습니다
참고 : ChatGPT

###(3) year, month, day, hour, minute, second 데이터 개수 시각화하기   
이 부분에서 오류가 나는부분은 한개의 plot에 여러개의 인수를 한번에 넣으려고 해서 그런거 아닐까 생각이 듭니다 시간이 없어서 고친 코드까지는 전달 못해드렸네요! 

```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```

