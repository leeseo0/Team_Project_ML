# Team_Project_ML

- 프로젝트 데이터 : https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics
- 협업 툴 : Google docs, Slack
- 기술 스택 : Python, Google Colab, jupyter notebook
- 프로젝트 기간 : 2023.06.12-2023.06.23
---
팀 멤버
* 최재혁 
* 김찬동
* 김민희
* 윤지훈
* 이서영
---
## 프로젝트 목적 및 배경
- 목적 : 통신사 고객 이탈 가능성을 예측하여 이탈 위험이 높은 고객에게 맞춤형 유지 전략을 제안
- 배경 : 이동 통신사 업계는 점유율 변화가 적은편으로 치열한 경쟁과 고객 요구의 다양화로 인해 고객 유지가 중요한 과제가 되고 있습니다. 기존 고객 유지 비용이 신규 고객 확보 비용보다 훨씬 낮기 때문에, 고객 이탈을 사전에 방지하는 것은 기업의 매출 보호와 장기적인 성장에 필수적입니다. 고객 이탈 가능성을 데이터 기반으로 예측하고, 효과적인 유지 전략을 설계하여 고객 유지율 향상을 달성하는데 기여하고자 합니다.

## 분석 과정
    1. 데이터 파악
    2. 프로젝트 목표 설정
    3. 데이터 전처리
    4. 데이터 시각화
    5. 데이터 인코딩
    6. 모델 학습(로지스틱 회귀, 랜덤포레스트, 그래디언트 부스팅, XGBoost, SVC, 의사결정트리, LightGBM)
    7. 모델 평가, 검증

## 분석 결과
위 모델들을 ROC AUC 곡선, feature importance에 대한 SHAP, 순열, Feature 중요도로 영향력 있는 Feature들 역시 검증해보았고, ROC-AUC 0.94로 가장 우수한 모델인 XGBoost 모델을 최종 모델로 선정했습니다.

## 인사이트 도출
1️⃣ 노년층과 1인 가구를 위한 타겟 마케팅 제안
가족 중심의 마케팅 전략으로 인해 노년층과 미혼 또는 부양가족이 없는 계층에서 이탈률이 높게 나타났습니다. 이를 바탕으로, 마케팅의 소외 대상이었던 노년층과 1인 가구를 대상으로 한 타겟 마케팅을 통해 이탈을 방지하고, 마케팅 비용을 효과적으로 절감할 것을 제안합니다.

2️⃣ 추천 혜택 강화 및 장기 제공 전략
가입, 약정 기간, 추천 횟수에 따른 이탈률 분석 결과, 추천 횟수가 2회 이상일 때 이탈률이 급격히 감소하는 경향이 확인되었습니다. 이에 따라, 추천 혜택을 1회만으로도 강화하고, 이를 장기간에 걸쳐 제공함으로써 고객의 이탈을 효과적으로 줄일 것을 제안합니다.

3️⃣ 신용카드 결제 방식 유도
계좌 인출 방식으로 요금을 지불하는 고객의 이탈률이 상대적으로 높은 것으로 나타났습니다. 따라서 신규 가입 고객에게 신용카드 결제 방식을 유도함으로써 이탈률 감소 효과를 기대할 수 있습니다.


---

## <프로젝트 개요>
![화면 캡처 2023-06-29 120224](https://github.com/jea0902/mini_project_ML/assets/62950552/cf5b7442-73e4-481d-b0b9-1f54849ce9e1)

![0-1](https://github.com/jea0902/Team_Project_ML/assets/62950552/bfe18309-ad8d-4c6a-8564-579b455b3b5f)

![0](https://github.com/jea0902/Team_Project_ML/assets/62950552/4d121bf6-72ac-483c-9f8e-56b90f19fda5)

![1](https://github.com/jea0902/Team_Project_ML/assets/62950552/72351349-af4a-43cd-b621-b443b77f6e75)

![2](https://github.com/jea0902/Team_Project_ML/assets/62950552/ec254ff5-e930-48ac-9075-eeba0c489a42)

![3](https://github.com/jea0902/Team_Project_ML/assets/62950552/63718ba9-069d-47e8-86a1-f2a67468affc)

![4](https://github.com/jea0902/Team_Project_ML/assets/62950552/ea27aebb-22d1-485e-82db-91c1ee6c4d51)

![5](https://github.com/jea0902/Team_Project_ML/assets/62950552/df7181aa-173c-4a3e-af72-876b09c653e6)

![6](https://github.com/jea0902/Team_Project_ML/assets/62950552/d9e3a625-3e13-4abd-a2f4-26b840bf2593)

![7](https://github.com/jea0902/Team_Project_ML/assets/62950552/5b0aa60d-b120-4c55-9934-c2df243ed638)

![8](https://github.com/jea0902/Team_Project_ML/assets/62950552/0165609d-4ef6-4f3b-b2c6-97de11b17228)

---

