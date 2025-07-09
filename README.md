super store sale prediction by end-to-end pipeline
Problem Statement:Predict sales based on various product, customer, and order-related features.
The dataset includes information such as:
Product category and sub-category
Segment and region
Order and shipping dates
Quantity, discount, and profit

What This Project Covers:
✅ Cleaning and handling missing dates
✅ Encoding categorical variables
✅ Train-test split
✅ Building an end-to-end pipeline (Scaler + XGBoost)
✅ Actual vs Predicted sales comparison
✅ Model evaluation with:Test MSE and R²

Technologies Used:
Python
Pandas, NumPy
scikit-learn
XGBoost
Matplotlib (for visualization)
5-fold Cross-Validation

Results:
mse : 0.05412224921560014
r2_score : 0.9787518752924779
with cross_val:
Cross-Validated MSE Scores: [0.05758222 0.06862881 0.06689012 0.04542323 0.0545902 ]
Mean MSE: 0.05862291608265206
Mean RMSE: 0.24146758562559872

Sample Predictions:
Actual Sales  Predicted Sales
6.336486         6.120512
3.628917         3.565184
3.645450         3.910401
5.361564         5.489681
5.149167         5.300552
4.606529         4.645870
5.832416         5.749583

How to run:
git clone https://github.com/zaralrubaie/superstore-price-prediction-.git

Open the notebook:
jupyter notebook superstore-sales.ipynb


Author:
Zahraa Rubaie
📍 Dubai, UAE
