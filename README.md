# Third-Task

📝 Project Workflow

1️⃣ Data Preprocessing
Converted categorical variables like yes/no to 1 and 0.
One-hot encoded multi-category features like furnishingstatus.
Checked for missing values and ensured clean data.

2️⃣ Feature Scaling
Applied MinMaxScaler to normalize numerical features for better model convergence.

3️⃣ Model Selection & Hyperparameter Tuning
Applied Linear Regression as the base model.
Used RandomizedSearchCV for hyperparameter tuning.
Chose R² Score (r2) as the evaluation metric to measure how well the model explains the variance in house prices.

4️⃣ Regression Line Plotting
Plotted the regression results to visualize predictions vs actual prices.
Explanation:
The red dashed line represents the ideal line where predicted prices perfectly match the actual prices. Points closer to this line indicate better predictions.

5️⃣ Model Interpretation
Extracted the coefficients from the trained regression model to interpret the relationship between features and house price. Higher positive coefficients suggest that increasing this feature increases house price.

📊 Key Results

Best R² Score after tuning: 0.45
Interpretation of key influential features based on regression coefficients.
Visualization of prediction accuracy through regression plots.