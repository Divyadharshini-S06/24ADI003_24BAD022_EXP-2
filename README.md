To implement and evaluate Linear Regression and Logistic Regression models using real-world datasets, including data preprocessing, model training, evaluation, visualization, and optimization.

Scenario 1: Ocean Water Temperature Prediction (Linear Regression)
Dataset

Source: Kaggle (Public)
Name: CalCOFI Oceanographic Dataset
Link: https://www.kaggle.com/datasets/sohier/calcofi

Target Variable
T_degC – Water Temperature (°C)

The CalCOFI dataset was loaded from Kaggle and relevant numerical features such as depth, salinity, oxygen, latitude, and longitude were selected. Missing values were handled using median imputation, and the data was scaled using StandardScaler. The dataset was split into training and testing sets, after which a Linear Regression model was trained to predict ocean water temperature. Model performance was evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score. Visualizations such as actual vs predicted temperature plots were generated, and model performance was further optimized using Ridge and Lasso regularization techniques.



Scenario 2: LIC Stock Price Movement Prediction (Logistic Regression)
Dataset
Source: Kaggle (Public)
Name: LIC Stock Price Data
Link: https://www.kaggle.com/datasets/debashis74017/lic-stock-price-data

Target Variable
Price Movement
1 → Close > Open
0 → Close ≤ Open

The LIC stock price dataset was obtained from Kaggle and a binary target variable indicating price movement was created based on opening and closing prices. Missing values were handled using median imputation, and feature scaling was applied using StandardScaler. The dataset was then split into training and testing sets, and a Logistic Regression model was trained to classify stock price movement. The model was evaluated using accuracy, precision, recall, F1-score, confusion matrix, and ROC curve. Feature importance was analyzed using model coefficients, and performance was optimized through hyperparameter tuning with regularization using GridSearchCV.



# 24ADI003_24BAD022_EXP-2
