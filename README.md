# 🌤️ Weather Dataset — Exploratory Data Analysis (EDA)

This project focuses on understanding how various weather features relate to **Temperature (°C)**.  
The analysis includes data cleaning, visualization, correlation study, and extracting insights that help understand environmental patterns.

---

## 📊 Correlation of Features with Temperature (°C)

Below is the correlation plot generated during the analysis:

![Correlation Plot](correlation_plot.png)

---

## 📝 Findings & Results

### ✅ Strong Positive Correlation
- **Apparent Temperature (°C)** has a **perfect positive correlation** with Temperature.  
  This means the “felt” temperature rises almost identically to actual temperature.
- **Visibility (km)** shows a **moderate positive correlation**, meaning clearer atmospheric conditions often come with warmer temperatures.

### ⚠️ Weak or No Correlation
- **Wind Speed**, **Wind Bearing**, and **Pressure** show **near-zero correlation** with temperature.  
  These variables have almost no influence on temperature variations in this dataset.

### ❌ Negative Correlation
- **Humidity** has a **moderate negative correlation**, suggesting higher humidity is associated with lower temperature.
- **Precipitation Type** also negatively correlates with temperature, indicating cooler conditions during precipitation events.

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


1. Clone the repository:
   ```bash
   git clone <your-repo-url>


