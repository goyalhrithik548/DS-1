# DS-1
# *Weather Prediction Dashboard*

## *Project Overview*
This project is a *Weather Prediction System* that uses machine learning to predict weather conditions (such as temperature and weather code) based on various meteorological features. It is designed to process historical weather data for two major cities, *Delhi* and *Mumbai, using the **Random Forest* algorithm. 

By integrating *real-time weather predictions* with historical data, this system enables users to view weather trends and predictions through an interactive dashboard. The dashboard is powered by *NocoDB*, a no-code platform that visualizes and stores weather data, enabling users to track real-time and historical weather patterns.

### Why It Matters
- The system provides *predictive insights* on weather, allowing users to plan ahead for various activities based on temperature and conditions.
- It allows *real-time weather forecasting* and data visualization, helping users keep track of the latest forecasts and compare them with historical trends.

---

## *Key Features & Technologies*

### *Key Features*:
- *Weather Prediction*: Utilizes historical weather data and machine learning models to predict temperature and weather conditions.
- *Real-Time Forecasting: Integrates with **Visual Crossing API* for live weather data, displaying current conditions and temperature.
- *Historical Data Analysis*: Uses historical weather data for training and comparison of predictive accuracy.
- *Interactive Dashboard: The weather predictions and historical trends are visualized using **NocoDB*, allowing users to explore the data with various graphical and tabular representations.

### *Technologies Used*:
- *Machine Learning*:
  - *Random Forest Classifier* for weather classification (weather code prediction).
  - *Random Forest Regressor* for temperature prediction.
- *Data Visualization*:
  - *NocoDB*: Used to create an interactive, no-code dashboard for data visualization.
- *API Integration*:
  - *Visual Crossing API* for fetching real-time weather data.
- *Data Processing & Handling*:
  - *Pandas* for data manipulation.
  - *NumPy* for numerical operations.
  - *Matplotlib* for visualizing predicted and actual weather data.

### *Data Source*:
- The historical weather data used for training and predictions was obtained from *Open-Meteo*.
  - Weather Data Download Link: [https://open-meteo.com/](https://open-meteo.com/)

---

## *Setup Instructions*

### *Pre-Requisites*:
- Python (preferably Python 3.6 or later)
- Install the necessary libraries (pandas, scikit-learn, matplotlib, requests, supabase-py)

### *Steps to Run the Project*:

1. *Clone the Repository*:
   - Clone the project to your local machine using:
   bash
   git clone https://github.com/your-username/weather-prediction-dashboard.git
   

2. *Install Required Libraries*:
   - Navigate to the project directory and install the dependencies using:
   bash
   pip install -r requirements.txt
   

3. *Download Weather Data*:
   - Download the historical weather data for Delhi and Mumbai from *Open-Meteo* at [Open-Meteo](https://open-meteo.com/).
   - Save the files as delhi-jan-dec-2024.csv and mumbai-jan-dec-2024.csv in the project directory.

4. *Supabase Integration*:
   - Sign up and create a project on *Supabase* (if you don’t have one already).
   - Insert your *Supabase project credentials* into the code where database connections are initialized.
   - Ensure your Supabase table is ready to store predictions (use the table weather_pred for predictions and real-time data).

5. *Run the Weather Prediction Script*:
   - Execute the script to train the models, make predictions, and upload data to Supabase:
   bash
   python weather_prediction.py
   

6. *View the Results*:
   - After running the script, you can view the predictions and historical weather data visualized in your *NocoDB* dashboard.
   - You can explore the predictions by visiting the NocoDB interface for your project.

---

## *Contributing*:
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Ensure that your changes do not break the existing functionality and are well-documented.

---

## *License*:
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## *Coders*:
1. *Hrithik Kumar*  
   Email: [goyalhrithik548@gmail.com](mailto:goyalhrithik548@gmail.com)

2. *Shaik Anisah Firdaws*  
   Email: [anisahfirdaws1810@gmail.com](mailto:anisahfirdaws1810@gmail.com)]
