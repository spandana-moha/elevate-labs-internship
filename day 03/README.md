# Day 03 - Linear Regression

📌 Task Objective
- Implement and understand simple and multiple linear regression using scikit-learn

🧰 Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

📂 Dataset
- House Price Prediction dataset (Housing.csv)

📋 Steps Followed
1. **Imported and explored the dataset**
   - Checked nulls, datatypes, and correlation
2. **Preprocessed the data**
   - Verified that there were no missing values in the dataset
   - Encoded categorical variables (e.g. mainroad, guestroom) into numerical format using label encoding and one-hot encoding
   - Scaled all numerical features using 'MinMaxScaler' to normalize them between 0 and 1
4. **Split the data**
   - Train-test split using 'train_test_split'
5. **Built the model**
   - Used 'LinearRegression()' from 'sklearn.linear_model'
6. **Evaluated model**
   - Metrics: MAE, MSE, and R²
7. **Plotted results**
   - Plotted regression line and compared predicted vs actual
8. **Interpreted coefficients**
   - Understood impact of each feature on the output

📊 Key Insights
- The dataset had no missing values and consisted of both numerical and categorical features
- Key features like 'area', 'bedrooms', and 'stories' showed strong positive correlation with 'price'
- Categorical features such as 'furnishingstatus', 'mainroad', and 'airconditioning' also contributed to price variation after encoding
- After scaling and preprocessing, the Linear Regression model achieved an R² score of **0.6657**, indicating how well the model explains price variation
- Regression coefficients revealed that:
  - 'area' had the highest positive impact on price
  - Features like 'hotwaterheating' and 'airconditioning' also had notable contributions
- The model was evaluated using MAE and MSE to ensure accuracy on the test data

