**Tech Stack Used:**

**Languages**

- Python

**Libraries**

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

**Machine Learning**

- Train/Test Split
- LSTM-based Time-Series Forecasting
- MinMax Scaling
- Model Evaluation (MAE, MSE, RMSE)

**Unsupervised Learning**

- Z-score

**AI / Automation**

- Performance scoring
- Rule-based AI recommendations


**Task 1: Exploratory Data Analysis (EDA)**

- LV Active Power
- Wind Speed
- Theoretical Power Curve
- Wind Direction


  
**Task 2: Time Series Forecasting (Supervised Learning)**

Built LSTM forecasting models for all 4 variables:

- Variable	             - Model Used	  -  Output
- LV Active Power (kW)	 - LSTM	        - Predicted Power
- Wind Speed (m/s)	     - LSTM	        - Future Wind Speed
- Theoretical Power(kWh) - LSTM        	- Expected Curve
- Wind Direction (°)	   - LSTM         -  Next Direction

**Performance metrics used:**

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root MSE (RMSE)



**Task 3: Unsupervised Learning – Anomaly Detection**

**Detected underperforming points using:**

- Isolation Forest
- Deviation from theoretical power curve
- Z-score-based anomaly detection




**Task 4: AI Turbine Performance Score**

->Score = (Actual Power / Theoretical Power) * 100

Performance categories:

  **Score**   	**Status**
 - 80–100	     - Good
 - 50–80	     - Moderate
 - 0–50	       - Poor
