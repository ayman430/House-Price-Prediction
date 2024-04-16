# House-Price-Prediction
Our objective is to accurately predict house prices by leveraging a selection of pertinent features and detailed descriptions encompassing the property, its location, and its amenities

## Used Tools:
- Numpy
- Pandas
- Matplotlip and Seaborn
- Sklearn
- Pipline
- RandomForestRegressor
- GridSearchCV

## NoteBook Cotains:
- Import dependencies and load CSV data file.
- Explore the data using info() and describe() methods.
- Check the number of unique values in each column.
- Analyze each feature to determine its usefulness for the model.
- Clean the data by removing irrelevant features.
- Fill NaN values appropriately.
- Create a pipeline consisting of:
    - Imputation using the most frequent value and one-hot encoding for categorical data.
    - Imputation using the mean for numerical values.
    - Model training.
- Fine-tune the RandomForestRegressor using GridSearchCV to identify the best hyperparameters.
- Utilize the best model for predictions

## Conclusion 
Upon analysis, it's evident that our dataset lacks coherence and validity for real-world applications. The high error rate and ambiguity of most features render them unsuitable for accurate predictions. Therefore, it's essential to acknowledge that our findings are primarily valuable for learning purposes and illustrating machine learning concepts rather than for practical deployment in real-world projects.
