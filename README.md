# 🔋EV Vehicle Demand Prediction

This repository contains a machine learning project that forecasts Electric Vehicle (EV) adoption trends across Washington State counties. The predictions provide insights for charging station demand planning and EV infrastructure development.

---
## 🎯 **Project Goals**

- Explore and analyze EV registration data by county

- Preprocess and clean real-world datasets

- Engineer time-series features (lags, rolling averages, growth metrics)

- Train and evaluate a Random Forest Regressor

- Forecast EV adoption for the next 36 months

- Build a Streamlit app for interactive visualization and county-level insights.

---

## 🛠️ **Tech Stack**

**Language** : Python

**Libraries** : pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels

**Model** : RandomForestRegressor

**App Framework** : Streamlit

**IDE** : Google Colab, VS Code

**Version Control** : Git + GitHub

---

# 📂 Project Structure  

EV_Vehicle_Charge_Demand/  
├── EV_Vehicle_Charging_Demand_Prediction.ipynb   # Jupyter Notebook  
├── app.py                                       # Streamlit App  
├── forecasting_ev_model.pkl                     # Trained ML model  
├── preprocessed_ev_data.csv                     # Cleaned dataset  
├── ev-car-factory.jpg                           # UI image  
├── requirements.txt                             # Project dependencies  
├── README.md                                    # Documentation

---

## ⚙️ **Installation & Usage**

- Clone the repository

- git clone https://github.com/Supraja1125/Ev-vehicle-demand-prediction.git
cd Ev-vehicle-demand-prediction


- Install dependencies

- pip install -r requirements.txt


- Run Jupyter Notebook (for model training & forecasting)

- jupyter notebook EV_Adoption_Forecasting.ipynb


- Launch the Streamlit App

- streamlit run app.py

---

## 📈 **How It Works**

- Registration data grouped by county & year

- Feature engineering: lag variables, rolling means, growth slopes

- Random Forest model trained on historical EV adoption trends

- Forecast horizon: 36 months into the future

- Streamlit app enables county-level adoption comparisons & visual insights

---

## 📊 **Sample Visualizations**

<img width="599" height="361" alt="image" src="https://github.com/user-attachments/assets/f744edd7-0dcb-4ba2-ac37-c0d872e2b327" />

<br>

<img width="494" height="507" alt="image" src="https://github.com/user-attachments/assets/1f63f01b-ef62-4361-a71d-bf14c45b026b" />

<br>

<img width="601" height="495" alt="image" src="https://github.com/user-attachments/assets/1e666ea4-c7d4-48fe-9c3b-f3e811eae56a" />


