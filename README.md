# [TAVE] image_classification
[제조공정 분야] 의류작물 불량 검출을 위한 이미지 분석

[참여자] 김수민, 원정문

[기간] 2021/12/22 ~ 2022/01/09


***

### [공정 분석 딥러닝 전체 플로우]
1. 불량 이미지와 정상 이미지 분류(레이블링)
2. 학습을 위한 data serialization(TFRecord)
3. 학습 데이터셋에 데이터 증강 적용(filp, rotation, traslation)
4. inception 이미지 모델로 classification 학습(모델 저장)
5. 알고리즘 구동 및 CSV 결과 저장 완료


* 플로우 시각화
![딥러닝실무흐름](https://user-images.githubusercontent.com/29356103/148681903-b80c4176-253f-4a2f-8b50-0d47bfa9f7a1.PNG)

***

* 불량 이미지 예시

![불량이미지](https://user-images.githubusercontent.com/29356103/148681905-aaad0e06-fc35-4dab-9b16-2de2fa822094.PNG)



* 모델 평가 기준

![정밀도재현성](https://user-images.githubusercontent.com/29356103/148681906-103bd9df-17c2-49fe-899c-c192b0d1d47d.PNG)


