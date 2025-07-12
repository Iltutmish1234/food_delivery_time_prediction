🛵<b> Food Delivery Time Prediction </b>
<br>📌<b> Objective: </b>
<br>This project aims to predict food delivery times using machine learning models, based on a variety of factors such as customer and restaurant location, traffic, weather, and more. We used both Linear Regression and Logistic Regression techniques to approach the problem from both continuous and classification perspectives.

📁<b> Project Phases:</b> <br>
🔍<b> Phase 1: Data Collection & Exploratory Data Analysis (EDA)</b>
<br>Data Import: Loaded dataset Food_Delivery_Time_Prediction.csv.<br>

<b>Preprocessing:</b>
<br>Handled missing values.<br>
Encoded categorical features like traffic and weather.<br>
Normalized continuous features like distance and order cost.<br>

<b>EDA:</b>
<br>Performed descriptive statistics.<br>
Checked correlation with target variable (Delivery_Time).<br>
Detected outliers using boxplots.

<b>Feature Engineering:</b>
<br>Calculated distance using Haversine formula.<br>
Created time-based features (e.g., Rush Hour indicator).

🤖<b> Phase 2: Predictive Modeling </b>
📈 <br>Linear Regression (Continuous Prediction)<br>
Goal: Predict actual delivery time.<br>

Features: Distance, Order Cost, Weather, Traffic, etc.<br>

<b>Metrics:</b>
<br>Mean Squared Error (MSE)<br>
R-squared (R²)<br>
Mean Absolute Error (MAE)<br>

🔢<b> Logistic Regression (Classification)</b>
<br>Goal: Classify delivery as Fast or Delayed.<br>
Features: Traffic Conditions, Weather, Delivery Person Experience, etc.<br>

<b>Metrics:</b>
<br>Accuracy<br>
Precision<br>
Recall<br>
F1-Score<br>
Confusion Matrix

📊 <b>Phase 3: Reporting & Insights</b>
<br>Model Comparison: Evaluated and compared both models.<br>

<b>Visualizations:</b>
<br>Pair plots, scatter plots, box plots<br>
Confusion matrix and ROC curve<br>

<b>Insights & Recommendations:</b>
<br>Optimize delivery routes<br>
Increase staff during peak traffic<br>
Improve delivery staff trainin



🛠️ <b>Technologies Used:</b>
<br>Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)<br>
Jupyter Notebook<br>
Machine Learning: Linear & Logistic Regression
