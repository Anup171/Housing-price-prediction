# California Housing Price Prediction

This project predicts median housing prices in California using socioeconomic and geographical data. It demonstrates a complete end-to-end machine learning workflow — including data preprocessing, model training, evaluation, feature importance analysis, and market insight generation. The project serves as a professional portfolio piece for applied data science and predictive modeling.

---

## Project Overview

The goal of this project is to build a regression model capable of estimating median house values based on features such as median income, average rooms, house age, and geographic coordinates. The project emphasizes interpretability and practical insights, showing how data-driven predictions can inform real estate market decisions.

---

## Key Features

- **Data Preprocessing**
  - Handle missing values and scale numerical features.
  - One-hot encode categorical variables.
  - Group locations using Latitude and Longitude for geographic insights.

- **Model Training**
  - Trains multiple models including Linear Regression, Ridge, and Random Forest.
  - Selects the best model using GridSearchCV with RMSE-based evaluation.

- **Feature Importance Analysis**
  - Ranks features contributing most to median house price predictions.

- **Learning Curve Evaluation**
  - Plots training vs. validation RMSE to diagnose bias or variance.

- **Market Insights Generation**
  - Identifies high-value geographic zones (top 20% median prices).
  - Generates price predictions for three buyer segments:
    - Budget
    - Mid-range
    - Luxury

---

## Example Output

High-Value Areas Identified:
Found 15 areas with median prices > 80th percentile
Top 3 price drivers: MedInc, AveRooms, HouseAge

Price Predictions for Segments:
Budget: $180,000
Mid-range: $310,000
Luxury: $520,000

---

## Project Structure

 California-Housing-Price-Prediction
│
├── notebook.ipynb # Jupyter Notebook containing full workflow
├── README.md # Documentation file
└── requirements.txt # Dependencies

---

## Installation

Clone this repository and install dependencies.

```bash
git clone https://github.com/your-username/california-housing-price-prediction.git
cd california-housing-price-prediction
pip install -r requirements.txt
🚀 Usage
Launch the notebook:

bash
Copy code
jupyter notebook notebook.ipynb
Run all cells sequentially to:

Preprocess data

Train models

Evaluate performance

Generate insights and predictions

Technologies Used
Python

Pandas, NumPy — Data manipulation and processing

Scikit-learn — Machine learning models and evaluation

Matplotlib, Seaborn — Visualization

Jupyter Notebook — Interactive analysis

Evaluation Metrics
Root Mean Squared Error (RMSE) for model performance

R² score for explained variance

These metrics help compare and select the most effective regression model.

Results & Insights
Median Income and Room Count are the strongest predictors of housing value.

The Random Forest model provided the lowest RMSE and best generalization.

High-value zones were concentrated in regions with above-average income and newer houses.

Future Enhancements
Integrate geospatial heatmaps for visualizing high-value clusters.

Extend model with deep learning for non-linear relationships.

Deploy model as a real-time API or Streamlit dashboard.

Author
Anup S. Bandarkar
B.Tech CSE (Data Science) @ BMS College of Engineering