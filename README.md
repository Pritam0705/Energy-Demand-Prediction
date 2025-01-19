## Energy Demand Prediction

This project focuses on building time-series models to predict energy consumption, greenhouse gas (GHG) savings, and EV charging behavior at electric vehicle (EV) charging stations. The models leverage advanced machine learning techniques to identify patterns, capture temporal dependencies, and enhance forecasting accuracy, aiding sustainable energy management.  

### Features
- **Time-Series Forecasting:** Models energy demand, GHG savings, and charging behavior over time.
- **Advanced Machine Learning Models:** Employs LSTM, N-BEATS, and tree-based models for high-performance predictions.
- **Comparative Analysis:** Benchmarks performance of various regression models to identify the most accurate approach.
- **Interactive Visualization:** Dashboards to visualize energy trends, model predictions, and key performance metrics.

### Dataset
1. **Source:**
Data includes EV charging sessions, energy usage, and GHG savings information.
Electric Vehicle Charging Station Usage, Palo Alto, California  
https://data.cityofpaloalto.org/dataviews/244892/ELECT-VEHIC-CHARG-STATI-66721/  

2. **Structure:**
Charging Data: Records of charging session duration, energy consumed, and station IDs.  
Data cleaning, handling missing values, and feature engineering (e.g., time-based features like hour of day, day of week).

### Models Used
1. **Baseline Models:**  

- Decision Tree (Accuracy: 69.1%)
- Random Forest (Accuracy: 72.3%)
- Linear Regression (Accuracy: ~64%)

2. **Advanced Models:**  

- N-BEATS: Achieved a Mean Absolute Percentage Error (MAPE) of 28.9%.
- LSTM: Demonstrated superior performance with a MAPE of 22%, effectively capturing temporal dependencies.

### Workflow
1. **Data Preprocessing:**

- Data cleaning and feature engineering to extract time-based patterns.
- Normalization for efficient training of machine learning models.

2. **Model Development:**

- Baseline models: Decision Tree, Random Forest, Linear Regression.
- Advanced models: LSTM and N-BEATS for capturing temporal and sequential patterns.

3. **Evaluation Metrics:**

- Accuracy for baseline models.
- MAPE and RMSE for time-series models to assess forecasting precision.

### Results from LSTM
![image](https://github.com/user-attachments/assets/728dc690-0e94-44e4-b437-c7848a20e567)

![image](https://github.com/user-attachments/assets/f3a66a37-4f11-40eb-9585-616907381a7f)

![image](https://github.com/user-attachments/assets/dbd50412-4be2-49a6-b69d-58507c442b16)


