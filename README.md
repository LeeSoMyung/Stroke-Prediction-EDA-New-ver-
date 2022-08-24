# Stroke-Prediction-EDA-New-ver-

### ML PROJECT

#### * Title : Stroke Prediction EDA

#### * Context
###### - 뇌졸중은 뇌에 혈액을 공급하는 혈관이 막히거나(뇌경색) 터져서(뇌출혈) 사망에 이르거나 신체장애가 나타나는 질환
###### - 세계보건기구에 따르면, 뇌졸중은 전 세계적으로 2번째의 주요 사망 원인이며, 전체 사망의 약 11%를 차지

#### * Stroke Prediction
###### - 성별, 연령, 나이, 다양한 질병 및 흡연 상태와 같은 상황를 기반으로 환자가 뇌졸중에 걸릴 가능성이 있는지 예측하고자 함

#### * Contents
###### - 1) Load Data
###### - 2) Exploratory Data Analysis (EDA)
###### - 3) Data Preprocessing
###### - 4) ML 5-Model Evaluation
###### - 5) Conclusion

#### * Attribute Info
###### - id : unique identifier
###### - gender : "Male", "Female", "Other"
###### - age : age
###### - hypertension : 0 --> doesn't have, 1--> have
###### - heart_disease : 0 --> doesn't have, 1--> have
###### - ever_married : "Yes", "No"
###### - work_type : "children", "Govt_jov", "Never_worked", "Private", "Self-employed"
###### - Residence_type : "Rural", "Urban"
###### - avg_glucose_level : average glucose level in blood
###### - bmi : body mass index
###### - smoking_status : "formely smoked", "never smoked", "smokes", "Unknown"
###### - stroke : 0 --> doesn't have, 1--> have
###### * "Unknown" in smoking_status means that the info is unavailable for this patient
###### * Source : https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

#### *Machine Learning Model
###### - 1) Logistic Regression
###### - 2) XGBoost
###### - 3) KNN
###### - 4) Random Forest
###### - 5) SVM

#### * CONCLUSION
###### - Acc가 가장 높은 모델은 약 94%로 Random Forest
###### - 본 프로젝트에서는 임계값을 디폴트 값(0.5)으로 설정하였지만,
###### precision과 recall 값을 적절히 조절하기 위해 
###### 임계값을 낮춰야 할 필요성을 



