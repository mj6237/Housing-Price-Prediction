
# California Housing Price Prediction 

This project implements a Machine Learning solution to predict housing prices in California using the **California Housing Dataset**. It covers the entire data science pipeline: from data cleaning and exploratory analysis to advanced feature engineering and model evaluation.

## 🚀 Performance
* **Model:** Random Forest Regressor.
* **Accuracy (R-squared Score):** **81.2%**.
* **Objective:** Predict the `median_house_value` for California districts.

## 🛠️ Tools & Technologies
* **Language:** Python
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn

## 📋 Key Features
1. **Data Preprocessing:** Handled missing values and verified data integrity.
2. **Exploratory Data Analysis (EDA):** Visualized price distribution based on geographical location (Latitude/Longitude) to identify high-value clusters.
3. **Feature Engineering:** Improved model performance by creating derived features:
   * **Rooms per Household:** Average rooms per home.
   * **Bedrooms per Room:** Ratio of bedrooms to total rooms.
   * **Population per Household:** Average occupants per home.
4. **Categorical Encoding:** Converted `ocean_proximity` into numerical format using One-Hot Encoding for model compatibility.

## 📊 Visualization
The project includes a geographical scatter plot that demonstrates the correlation between proximity to the coast and higher housing prices.



## ⚙️ How to Run
1. Clone this repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Open `house_price.ipynb` in Jupyter Notebook or VS Code and run all cells.

---


Since you are a **Cybersecurity Instructor**, having a clean and documented GitHub repository like this shows your attention to detail and professional coding standards!
