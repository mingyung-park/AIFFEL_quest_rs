# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 박민경
- 리뷰어 : 양지웅


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**

    3가지 모델을 사용했고 정확도 85%를 넘기었다.

    ![image](https://github.com/user-attachments/assets/5173f7ae-8170-4dac-acee-c5ae11c6ff83)

    임베딩 메트릭스를 분석하여 단어간 유사도를 분석하였다.

    ![image](https://github.com/user-attachments/assets/f6cbc67b-60d2-40ef-a3f3-778a2cdec289)

- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

    정의한 함수에 대해 어떤 역할을 하는지 주석으로 잘 작성해주었다.

    ![image](https://github.com/user-attachments/assets/5afed64c-23c2-4d38-8508-574dde766ba7)

- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**

    W2V 모델을 쓸 때 벡터의 차원이 100차원으로 커져서 모델 용량도 같이 올리는 시도를 하였다.

    또한 여러 에폭에 대한 실험을하고 오버피팅이 자주나는 에포크를 기준으로 중지하는 방법도 좋았다.

    ![image](https://github.com/user-attachments/assets/ec06aa55-72e3-4da1-b790-196af54ab6ae)

- [x]  **4. 회고를 잘 작성했나요?**

    회고에 대해 잘 작성하였다. 공감가는 부분이 많았다.
    
    ![image](https://github.com/user-attachments/assets/a8eab5aa-b0f6-426b-9bd0-ada592e83f7b)
        
- [x]  **5. 코드가 간결하고 효율적인가요?**

    시각화하는 부분이 많은데 이를 함수화한 것이 좋았다. 저는 그러지 않아서 코드 중복이 많았는데 코드 중복을 줄이는 좋은 접근인 것 같다.

    ![image](https://github.com/user-attachments/assets/f357959c-0f69-4314-8978-357789c8f0a3)

# 회고(참고 링크 및 코드 개선)
```
민경님처럼 모델 크기를 좀 더 키웠으면 하는 아쉬움이 있다. 또한 리뷰를 통해 각 모델에서 반복되는 부분을 함수화 했으면 더 좋았을 것 같다는 점을 깨달았다.
각자의 접근법을 비교하고 피드백할 수 있는 좋은 리뷰였다.
```
