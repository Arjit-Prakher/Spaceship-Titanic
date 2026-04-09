# 🚀 Spaceship Titanic: Interstellar Prediction
Predicting which passengers were transported to an alternate dimension following a spacetime anomaly using Machine Learning.

## 📌 Project Overview
The Spaceship Titanic was an interstellar passenger liner that collided with a spacetime anomaly. To help rescue teams, this project uses machine learning to predict which passengers were "Transported" based on their personal data, cabin location, and spending habits.

### Key Objectives:
- Perform Exploratory Data Analysis (EDA) to find correlations.

- Implement Logic-Based Smart Imputation for missing values.

- Perform Feature Engineering on complex strings (Cabins and Passenger IDs).

- Evaluate model performance using Precision, Recall, and F1-Scores.

### 🛠️ Tech Stack
- Language: Python 3.14

- Libraries: Pandas & NumPy for data manipulation.

- Scikit-learn for machine learning and evaluation.

- Matplotlib & Seaborn for modern data visualization.

### 📊 The Workflow
1. **Smart Data Cleaning:** Instead of naive mean/mode imputation, this project uses behavioral and logical constraints:

2. **Behavioral Logic:** Setting luxury expenditures to 0 for all passengers in CryoSleep.

3. **Sub-group Statistics:** Imputing Age using the median of specific demographic groups.

### Feature Engineering
- Converted raw data into high-signal features:

- **Total Expenditure:** Aggregated spending across RoomService, FoodCourt, ShoppingMall, Spa, and VRDeck.

### Modeling
Tested multiple classification algorithms, including:

1. Logistic Regression (Baseline)

2. SVC

### 📈 Results & Evaluation
The final model achieved a balanced performance across both classes
(Transported vs. Not Transported).

|Metric | Score |
|-------|-------|
|Accuracy|0.78|
|Precision (Class 1)|0.77|
|Recall (Class 1)|0.79|
|F1-Score|0.78|

### Insights:
- CryoSleep is the strongest predictor of being transported.
- Spending habits significantly differ between those transported and those safe.

## About the dataset

| HomePlanet | The home planet of the passenger. |
| ---------- | ---------------|
| CryoSleep  | This is a kind of animation in which a passenger will be suspended during the whole voyage and remain confined to their cabin. |
| VIP | Indicates whether the person has opted for VIP service or not.|
| RoomService, FoodCourt, shopping mall, Spa, VRDeck | Commodities on which passengers of the spaceship can choose to spend. |
|Transported |	This is the target column. This indicates whether the passenger has been transported to another dimension or not. |


## Dataset
[Click here to visit](https://www.kaggle.com/datasets/himaanishaggarwal/spaceship-titanic?select=train.csv) 

### Presented By
[Arjit Prakher] Full-Stack Developer & ML Enthusiast