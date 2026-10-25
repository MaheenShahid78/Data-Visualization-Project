
#  Flight Delay Prediction and Visualization

## 📌 Project Overview

Flight Delay Prediction and Visualization is a data analytics and machine learning project that analyzes flight data to predict delays and visualize key patterns.

The project uses approximately **3 million flight records with 32 features** covering flights from January 2019 to March 2023. It combines data preprocessing, exploratory data analysis (EDA), XGBoost regression, SHAP-based model interpretation, and an interactive Power BI dashboard to understand flight delays and airline performance.

## 🎯 Objectives

- Analyze flight delay patterns across airlines, airports, and routes.
- Identify the major causes of flight delays.
- Explore trends in departure and arrival delays over time.
- Predict flight delays using machine learning.
- Interpret model predictions using SHAP.
- Develop an interactive Power BI dashboard for flight data visualization.

## 🛠️ Technologies Used

- **Python** — Data analysis and machine learning
- **Pandas & NumPy** — Data manipulation and preprocessing
- **Matplotlib & Seaborn** — Data visualization
- **Scikit-learn** — Data preprocessing and model evaluation
- **XGBoost** — Flight delay prediction
- **SHAP** — Model explainability
- **Power BI** — Interactive dashboard and business intelligence
- **Jupyter Notebook** — Data exploration and experimentation

## 📊 Dataset

The dataset contains approximately 3 million flight records and 32 columns.

**Dataset details:**
- **Time period:** January 9, 2019 – March 6, 2023
- **Records:** Approximately 3,000,000
- **Features:** 32

**Key features include:**
- Flight date, airline, and flight number
- Origin and destination airports
- Scheduled and actual departure and arrival times
- Departure and arrival delays
- Flight distance and airtime
- Taxi-in and taxi-out times
- Cancellation and diversion status
- Different causes of flight delays

## 🔄 Project Workflow

1. **Data Loading and Exploration:** Loaded the dataset and examined its structure, features, and missing values.
2. **Data Preprocessing:** Handled missing values, removed the cancellation code column due to excessive missing data, and prepared the data for analysis.
3. **Exploratory Data Analysis:** Investigated correlations, delay distributions, airline performance, and trends over time.
4. **Machine Learning:** Implemented an XGBoost regression model to predict flight delays.
5. **Model Evaluation:** Evaluated the model using R², Mean Absolute Error (MAE), and Mean Squared Error (MSE).
6. **Model Explainability:** Used SHAP plots to understand the influence of individual features on predictions.
7. **Dashboard Development:** Created an interactive Power BI dashboard to explore flight statistics and delay patterns.

## 🤖 Machine Learning Model

An **XGBoost Regression** model was implemented to predict flight delays using flight-related features.

### Model Performance

| Evaluation Metric | Result |
|---|---:|
| R² Score | 0.85 |
| Mean Absolute Error (MAE) | 6.7389 |
| Mean Squared Error (MSE) | 323.7970 |

These results are based on the model evaluation reported in the project report.

### Model Explainability with SHAP

SHAP was used to interpret the model and examine how different features influence its predictions.

The analysis highlighted:
- Distance and airtime as influential features in the model.
- Departure delay as an important factor affecting predicted arrival delays.
- Route-related features as significant contributors in individual predictions.
- Day of the week and destination as relatively less influential in the reported feature-importance analysis.

## 📈 Power BI Dashboard

An interactive Flight Analytics Dashboard was developed in Power BI to visualize key performance indicators and explore flight delay patterns.

### Dashboard Highlights

- **Total Airlines:** 18
- **Cancelled Flights:** Approximately 79,000
- **Diverted Flights:** 7,056
- **Total Flights:** Approximately 3 million
- **On-Time Arrival Rate:** 67%, compared with a target of 75%

### Visualizations

- Yearly departure and arrival delay trends
- Distribution of flight delay causes
- Taxi-in and taxi-out time comparisons by airline
- Arrival and departure delay comparisons across airlines
- Key performance indicators for flight operations
- Interactive airline selection using slicers and filters

## 🔍 Key Insights

- Late aircraft, National Aviation System (NAS), and carrier delays were identified among the common delay causes in the analysis.
- Flight delays decreased in 2020 and increased in the following years, reaching a reported peak in 2022.
- Delay patterns vary across airlines and routes.
- Weather-related delays were less frequent in the analysis but could cause significant disruptions.
- The dashboard helps users compare airline performance and explore operational trends.

## 💡 Recommendations

Based on the project findings, airlines can consider:

- Optimizing flight schedules during periods with higher delays.
- Improving aircraft turnaround processes.
- Monitoring routes associated with higher delays.
- Using historical delay patterns to support operational planning.
- Improving passenger communication about potential disruptions.

## 🚀 Future Improvements

- Develop a user-friendly application for entering flight details and obtaining delay predictions.
- Improve prediction accuracy through further feature engineering and model tuning.
- Evaluate models using additional validation strategies.
- Integrate more recent flight data to analyze changing delay patterns.
- Extend the dashboard with additional operational performance indicators.

## 🏁 Conclusion

This project combines data analytics, machine learning, explainable AI, and business intelligence to study flight delays and airline performance. The XGBoost model achieved an R² score of 0.85, while the Power BI dashboard provides an interactive way to explore delay trends, compare airlines, and understand potential causes of disruptions.

The project demonstrates how data-driven techniques can support better understanding and analysis of flight operations.

## 👥 Contributors

- **Maheen Shahid** maheenshahid0302@gmail.com
- **Hoor-Ul-Ain Wajid** hoorwajid3@gmail.com
