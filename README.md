# 🌤️ Weather Dataset — Exploratory Data Analysis (EDA)

This project focuses on understanding how various weather features relate to **Temperature (°C)**.  
The analysis includes data cleaning, visualization, correlation study, and extracting insights that help understand environmental patterns.

---

## 📊 Correlation of Features with Temperature (°C)

Below is the correlation plot generated during the analysis:

![Correlation Plot](https://github.com/Normal-repo/Time-series-Weather-Data-Analysis-Exploratory-Data-Analysis-EDA-/blob/main/co-relation.png)

---

## 📝 Findings & Results

### ✅ Features with **Strong Positive Influence**
These features increase as temperature increases:

- **Apparent Temperature (°C)**  
  - Shows a **perfect positive correlation**, meaning it rises almost identically with temperature.
- **Visibility (km)**  
  - Shows a **moderate positive correlation**, indicating clearer weather often corresponds to warmer temperatures.

### ❌ Features with **Strong Negative Influence**
Negative correlation does NOT mean “not useful” — it means the feature affects temperature in the opposite direction.  
We **do use these features** because they help the model understand cooling effects.

- **Humidity**  
  - Shows a **moderate negative correlation**, meaning high humidity is associated with lower temperature.
- **Precipitation Type**  
  - Also negatively correlated, showing that precipitation is likely during cooler conditions.

These features are important because they explain **why** temperature drops under specific weather patterns.

### ⚠️ Features with Weak or No Influence
These show very little relationship with temperature:

- **Wind Speed**
- **Wind Bearing**
- **Pressure (millibars)**

While they may not strongly affect temperature, they are still part of the dataset but have minimal impact on temperature prediction.

---

## 📁 Project Structure

📂 Weather-EDA
├── weather.ipynb
├── correlation_plot.png
├── README.md







## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  




