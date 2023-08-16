# Car Price Prediction

In this project, I have used Python to develop a linear regression model that predicts the prices of used cars from various datasets, based on features such as the car's age, mileage and engine specifications.

### Key Steps
* Data Loading: Loading all CSV data and neccessary libraries into the notebook.
* Data Cleansing: Cleaned the data by handling missing values and removing duplicates to ensure the quality of the data.
* Data Transformation: Data preoprocessing to uphold accuracy of the model by using one-hot encoding to convert categorical variables to numerical values.
* Prediction: Finding trends within the data and deploy the Linear Regression learning algorithm.

![alt text](https://github.com/tola923/Car_Price_Prediction/blob/master/corr%20plot.png)

### Model Development and Evaluation

Linear regression was chosen as the model of choice due to it's ease of interpretability. I used both scikit-learn and NumPy libraries to implement the linear regression algorithm. The model was trained on a portion of the dataset and validated using various evaluation metrics.

The model's performance was evaluated based on the R-squared (R2) score. This metric is the most useful in assessing how well the model predicts used car prices. The model produced an R2 value of 0.74.

### Folder Structure
* "filename".csv: CSV data of all car makes.
* corr plot.png: Correlation plot showing the relationship between variables within the combined car dataset.
* Car prediction notebook.ipynb: Notebook of code detailing all steps from data loading to prediction.

### Dataset Origin
* [Dataset](https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes)
