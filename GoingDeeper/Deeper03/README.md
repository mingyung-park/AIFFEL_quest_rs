# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 박민경
- 리뷰어 : 황수미


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
          <img src = "https://github.com/user-attachments/assets/53e29376-af19-431d-ac62-2a3d48f3c3fb">
          <img src = "https://github.com/user-attachments/assets/2fd381da-9a94-4182-820a-863bb5aafd30">
          <img src = "https://github.com/user-attachments/assets/94f8e24e-013a-4170-95f3-2cdf4a222673">
    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img src = "https://github.com/user-attachments/assets/e01560aa-016b-436c-ac60-70158d3e7262">
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img src = "https://github.com/user-attachments/assets/e3c8e903-ac12-4726-acd9-fd6e8aa00f55">
          <img src = "https://github.com/user-attachments/assets/ed2b57fa-73d5-4ea3-ba71-0282cf923716">
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img src = "https://github.com/user-attachments/assets/ad9ae9a9-83bc-4c64-8b83-ac987538b496">
          <img src = "https://github.com/user-attachments/assets/7a6ff588-8b7d-40c8-9e4c-25381b34f36a">
        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img src = "https://github.com/user-attachments/assets/fc0be962-8b22-42cc-802f-7091150861c2">


# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
- 저는 IoU 평균을 낼 때 막연히 다 더하고 샘플 개수로 나누어줄 생각만 했는데 신뢰구간까지 고려해서 box plot으로 보여주신 게 인상 깊었습니다.
- 각 블록별로 비교가 잘 되어 있고, CAM과 Grad-CAM의 차이점에 주목하여 결론을 내주셔서 도움이 많이 되었습니다.
