# Titanic Survival
## 專案說明
使用鐵達尼號沈船事件的資料來分析可能影響著當時人們存活率的因素。

## 建立模型
使用XGBoost、Stacking堆疊法來訓練模型，Stacking的base-models選用Decision Tree、KNN、SVC、Random Forest，meta-model則選擇Logistic Regression。

### 資料集
只採用Survived、Pcalss、Sex、Age、Sibsp、Parch、Fare及Embarked等特徵來做訓練。
## 架設 Flask API
![image](https://github.com/user-attachments/assets/0240cd7c-b826-4813-8cb9-64d5ca83f36f)
![image](https://github.com/user-attachments/assets/87b2cbf3-5f54-4947-95f2-a4174a8f1ca0)

## Docker
在Releases的Docker標籤處有此專案的tar檔。

![image](https://github.com/user-attachments/assets/9da0dd8e-96db-47f3-92af-40f0f9c986ba)
![image](https://github.com/user-attachments/assets/096de0d0-c6e6-4b58-bf30-9917f0876b77)

## 資料集來源
<https://www.kaggle.com/datasets/yasserh/titanic-dataset/data>
 

