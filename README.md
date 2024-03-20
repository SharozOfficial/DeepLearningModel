# DeepLearningModel
# Crop Production and Food Consumption Analysis

## Exploratory Data Analysis

Factors affecting crop production:
  1. Climatic Factors
  2. Rainfall
  3. Temperature
Topography – Area harvested
Import/Export
Population

![image](https://github.com/SharozOfficial/DeepLearningModel/assets/158645890/6d182ca2-6930-44f4-825c-2c3a77635d9a)

CROP PRODUCTION VS YEAR

![image](https://github.com/SharozOfficial/DeepLearningModel/assets/158645890/29012d27-e4d7-46db-bdd0-4665331c722d)

FACTORS VS YEAR

![image](https://github.com/SharozOfficial/DeepLearningModel/assets/158645890/3cc009ce-e4ce-4715-9951-78e2cf38de2d)

![image](https://github.com/SharozOfficial/DeepLearningModel/assets/158645890/122d34bf-6557-48ed-b305-1377b7993dce)

![image](https://github.com/SharozOfficial/DeepLearningModel/assets/158645890/7d6f0110-d4d5-4e55-bd29-7287a1c4553f)

![image](https://github.com/SharozOfficial/DeepLearningModel/assets/158645890/f22b190c-eee5-4763-830e-e084d4090197)

## MODEL SELECTION

- Coefficient of determination R²

![image](https://github.com/SharozOfficial/DeepLearningModel/assets/158645890/f0316631-a513-403d-9886-c3cd1dbec6ac)

LSTM vs Random Forest Regressor (Time-Series Analysis)
Computational Time : RFR > LSTM
GPU limitations & No. of units : RFR > LSTM (Reference: Evaluation and Comparison of Random Forest and A-LSTM Networks for Large-scale Winter Wheat Identification)

Transformation of Data:
“Slicing Window” - This approach moves a window through the time series data, adding a sequence of multiple data points to the input data with each step. 
Implemented on our Dataset with resultant as – (466, 75, 5) (466,)

Evaluation of loss curve
Crop Production:
Epochs = 50
Batch Size = 32
![image](https://github.com/SharozOfficial/DeepLearningModel/assets/158645890/d1f54a8b-18d0-42bc-82e9-029a050ca040)

Food Consumption:
Epochs = 30
Batch Size = 32
![image](https://github.com/SharozOfficial/DeepLearningModel/assets/158645890/978780a2-3532-4a5e-a113-3cb5d3b28e33)

Crop Production(Trained, Actual, Predicted) vs year
![image](https://github.com/SharozOfficial/DeepLearningModel/assets/158645890/ca6f2dd8-8f50-4885-a9d5-5ee7597a78df)

Food consumption (Trained, Actual, Predicted) vs year
![image](https://github.com/SharozOfficial/DeepLearningModel/assets/158645890/a6d8aba6-f20a-4c38-b60c-547ee5807a30)



















