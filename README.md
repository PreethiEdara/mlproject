## End to End Machine Learning Project
This project understands how the student’s performance (test scores) is affected by other factors such as gender, ethnicity, preparation course 
etc.  
**1. DATA INGESTION:**  
Dataset from kaggle having student information like gender, race ethnicity, parental level of education, writing score, reading score etc.
It has both categorical and numerical data.
**2. DATA TRANSFORMATION:**  
Implemented the data transformation where we will be performing necessary tasks such as handling categorical values,handling missing values  standard scaling using pipelines and saving the pickle in the artifact folder sing libraries like OnehotEncoder, StandardScaler, ColumnTransformer.
**3. MODEL TRAINER:**  
Used the regression algorithms like LinearRegression, KNeighbours Regressor, DecisionTree Regressor, XGBRegressor, CatBoostRegressor and ensemble methods including AdaboostRegressor, GradientBosstingRegressor, RandomforestRegressor.
**4. MODEL EVALUATION :**  
Performed the model evaluation using r2_score. LinearRegression model outperformed all the other models with r2_sore of ~0.88.
**5. MODEL DEPLOYMENT:**  
Deployed the model into AWS elastic beanstalk  

<img width="409" alt="image" src="https://user-images.githubusercontent.com/123542622/235497784-f9447377-5421-459c-843a-d5e556311a22.png">
<img width="445" alt="image" src="https://user-images.githubusercontent.com/123542622/235498067-dac05980-e155-4974-8d7b-123883ceb847.png">

