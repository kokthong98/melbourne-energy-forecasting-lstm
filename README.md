# Melbourne Electricity Usage Forecasting with LSTM

This project uses time series modeling and stacked LSTM (Long Short-Term Memory) neural networks to forecast household electricity usage in Melbourne, Australia. The workflow covers real-world data cleaning, feature engineering, modeling, and evaluation.

---

## 📈 Project Overview

- **Objective:** Predict household electricity usage in Melbourne using historical usage and weather data.
- **Techniques:** Data preprocessing, feature engineering, time series modeling, LSTM neural networks.
- **Tools:** Python, Pandas, scikit-learn, TensorFlow/Keras, Matplotlib/Seaborn, Google Collab.

---

## 🗂️ Dataset

- **Source:** Australian Energy Market Operator (AEMO) & Bureau of Meteorology (BOM)
- **Features:** Electricity usage (kWh), temperature, humidity, weather variables, datetime
- **Challenge:** Real-world energy usage is complex and noisy; limited features and some missing data

---

## 🛠️ Workflow

1. **Data Cleaning & Preparation**
    - Handle missing values, merge datasets, and format date-time fields
2. **Feature Engineering**
    - Create lag features, rolling averages, and combine weather with usage data
3. **Data Splitting**
    - Train/test split with appropriate time-based validation
4. **Modeling**
    - Build stacked LSTM neural network for sequence prediction
    - Tune hyperparameters (epochs, batch size, sequence length)
5. **Evaluation**
    - Metrics: RMSE, MAE, R² score
    - Visualization of predicted vs. actual usage

---

## 🔎 Results & Learnings

- **Performance:**  
  The LSTM model achieved modest prediction accuracy (R² ~0.3–0.4). Results reflect the challenge of forecasting real-world energy demand with limited features.
- **Key Takeaways:**
    - Data quality and feature selection are crucial for time series forecasting
    - LSTMs can model complex temporal relationships, but are sensitive to feature engineering and data quantity
    - Real business use-cases often require domain knowledge, external variables (e.g. holidays, occupancy)

---

## 💡 Next Steps / What I'd Improve

- Test other algorithms (Random Forest, XGBoost, SARIMAX)
- Incorporate additional data: calendar events, appliance usage, occupancy, etc.
- Deploy model in a dashboard (Power BI, Streamlit, etc.) for business use
- Refine feature engineering for better context/seasonality

---

## 📁 File Structure

---

## 📝 Disclaimer

This project is for learning and portfolio purposes. Results are not production-grade but demonstrate the full data science process—from data cleaning through advanced modeling and honest evaluation.

---

## 🔗 Contact

Feel free to connect or ask questions!  
[LinkedIn](https://www.linkedin.com/in/kok-thong-ong-71ab59221/) | kokthong98@gmail.com



