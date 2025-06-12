# Weather-Crop-Advisor
The Weather-Based Crop Advisor is a machine learning tool that recommends suitable crops and predicts yields using weather, soil, and regional data in Ghana. It helps farmers and policymakers make informed decisions to boost productivity, improve sustainability, and adapt to changing climate conditions.


## 📌 Key Features

- ✅ Crop recommendation based on temperature, rainfall, humidity, and soil data.
- 📈 Yield prediction using regression models.
- 🧠 Machine learning algorithms (Random Forest, XGBoost).
- 🔗 Data integration from SQL databases (e.g., Ministry of Agriculture).
- 📊 Export-ready for Power BI dashboards.
- 📍 Region-specific insights for major agro-ecological zones in Ghana.

---

## 📂 Dataset Description

The dataset (real or simulated) contains the following fields:

| Column           | Description |
|------------------|-------------|
| `date`           | Date of record |
| `region`         | Ghanaian region |
| `temperature`    | Avg daily temperature (°C) |
| `rainfall`       | Daily rainfall (mm) |
| `humidity`       | Relative humidity (%) |
| `soil_moisture`  | Soil moisture content (%) |
| `soil_type`      | Soil classification (Sandy, Clay, Loamy, etc.) |
| `crop_type`      | Crop grown (e.g. Maize, Cassava) |
| `yield_kg`       | Yield in kg/ha |

---

## 🧠 Machine Learning

- **Crop Recommendation**: `RandomForestClassifier`
- **Yield Prediction**: `RandomForestRegressor`, `XGBoost`
- **Feature Engineering**: Normalization, label encoding, missing data handling
- **Evaluation Metrics**: Accuracy, classification report, R² score

---

## 🛠️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com//aminayusif/weather-crop-advisor.git
   cd weather-crop-advisor


 ## 📌 Future Enhancements
Real-time weather API integration (e.g., OpenWeatherMap)

Mobile/web interface for field agents

Integration with Ghana's soil and agro-ecological zoning databases
