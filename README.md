<h1>🏡 California Housing Linear Regression Project</h1>

This project applies a Linear Regression model on the California Housing dataset to predict median house prices based on various neighborhood features.

<h1>📌 Objective</h1>

Predict the MedHouseValue (Median House Value in $100,000s) using features like:

- Median Income

- House Age

- Average Rooms

- Location (Latitude & Longitude), etc.

<h1>🔧 Tools & Libraries Used</h1>

- Python

- Scikit-learn

- Pandas

- Matplotlib & Seaborn

<h1>📊 Model Performance</h1>

- R² Score: 0.5757877060324508

- MSE (Mean Squared Error): 0.5558915986952444

<h1>🧪 Training Steps</h1>

- Loaded the dataset using fetch_california_housing()

- Performed basic EDA (with useful plots - just for fun!)

- Trained a Linear Regression model

- Evaluated it using R² Score and MSE

<h1>🧪 Training Workflow </h1>

- Data Loading : Used fetch_california_housing() from sklearn.datasets to load the dataset.

- Data Preparation : Converted data into pandas DataFrame for easy handling.

- Split into features (X) and target (y = MedHouseValue).

- Train-Test Split : Used train_test_split() with 80/20 split.

- Model Training : Trained a Linear Regression model using scikit-learn.

- Evaluation : Calculated R² Score and MSE to evaluate the model's performance.

<h1>🧠 PLOTS SECTION - IN ORDER TO SHOW OFF THE KNOWLEDGE</h1>

1. Distribution of the Target Variable (MedHouseValue)

Helps understand the spread and skew of the price data.

![image](https://github.com/user-attachments/assets/12bce6c4-04ee-4870-9a8a-9bcacc525536)


2. Median Income vs Median House Value

Shows one of the strongest positive correlations — richer neighborhoods = pricier homes.

![image](https://github.com/user-attachments/assets/0645ac12-e508-4e96-9629-e2643bc61a13)


3. Actual vs Predicted Plot

How close our model gets to real values — good for visual accuracy.

![image](https://github.com/user-attachments/assets/bf123cf5-5277-4ebf-88fe-ed9c3081396f)

<h1>⚡ How to Run</h1>

***Clone this repository***

1) git clone [https://github.com/your-username/california-housing-regression.git](https://github.com/HrP14/Sckit_California_Data_Set.git)

2) cd california-housing-regression

***Install requirements (if needed)***

1) pip install -r requirements.txt

Run the notebook using Jupyter or any Python IDE.


