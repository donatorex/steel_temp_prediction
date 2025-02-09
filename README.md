# Final project on the course “Data Science Specialist” from Yandex Practicum
This is my final project completed as part of the Data Science Specialist course from Yandex Practicum. The project is devoted to the development of a machine learning model for predicting the alloy temperature at the steel processing stage in a steel mill.

## Project Description
The goal of the project is to create a model that predicts the temperature of steel during the processing stage, which will optimize the heating process and reduce energy consumption. To achieve this goal, data from heating processes, alloying component additions and temperature measurements were used. The project includes data preprocessing, exploratory analysis, model training and model quality assessment.

## Results
- The LGBMRegressor model was developed and showed the best performance among the other models tested, with an MAE metric on the test sample equal to 5.78.
- The model can predict the final melt temperature with high accuracy, which helps to reduce energy consumption.
- Feature importance analysis identified key factors affecting temperature such as initial temperature, duration of heating and purge-stirring stages, and alloying component composition.
- Recommendations for businesses to improve the energy efficiency of the process, including optimizing the composition of alloying additives, were identified.

## Technology Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, CatBoost, LightGBM, SHAP, Phik

## Link to the project notebook

You can view the project notebook [here](https://github.com/donatorex/steel_temp_prediction/blob/main/steel_temp_prediction.ipynb) (in Russian).
