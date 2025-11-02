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

 California-Housing-Price-Prediction<br>
--> notebook.ipynb # Jupyter Notebook Workflow<br>
--> README.md # Documentation file<br>
--> requirements.txt # Dependencies<br>

---

## Installation

Clone this repository and install dependencies.

```bash
git clone https://github.com/your-username/california-housing-price-prediction.git
cd california-housing-price-prediction
pip install -r requirements.txt
```

## Technologies Used

- **Python**
- **Pandas**, **NumPy** — Data manipulation and processing  
- **Scikit-learn** — Machine learning models and evaluation  
- **Matplotlib**, **Seaborn** — Visualization  
- **Jupyter Notebook** — Interactive analysis  

---

## Evaluation Metrics

- **Root Mean Squared Error (RMSE):** Measures prediction error magnitude  
- **R² Score:** Indicates how much variance is explained by the model  

These metrics help compare and select the most effective regression model.

---

## Results & Insights

- **Median Income** and **Average Room Count** are the strongest predictors of housing value.  
- The **Random Forest** model achieved the lowest RMSE and best generalization.  
- **High-value areas** were concentrated where income levels and house conditions were above average.  

---

## Future Enhancements

- Integrate **geospatial heatmaps** to visualize high-value regions.  
- Extend the project with **deep learning** for non-linear patterns.  
- Deploy the model as a **real-time API** or **Streamlit dashboard** for interactive predictions.  

---

## Author

**Anup S. Bandarkar**  
_B.Tech CSE (Data Science) @ BMS College of Engineering_  
