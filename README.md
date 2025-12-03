# ✈️ Flight Delay Analysis & Prediction  
Understanding when, where, and why U.S. domestic flight delays occur.

## 📌 Overview  
This project analyzes over **539,000 U.S. flights** across **40 major airports** using **8 key features** to explore and predict flight delays.  
The goal is to identify **patterns**, **high-risk time windows**, **problematic routes**, and the **strongest predictors** of delay.

## 📊 Dataset  
The dataset includes detailed flight-level information:

| Feature          | Description |
|------------------|-------------|
| `id`             | Unique flight identifier |
| `airlines`       | Operating airline |
| `airportfrom`    | Departure airport |
| `airportto`      | Arrival airport |
| `timeofday`      | Scheduled departure period |
| `dayofweek`      | Day of the week (1–7) |
| `flightduration` | Flight duration in minutes |
| `delay`          | Arrival delay in minutes |
| `flightno.`      | Flight number |

Total rows: **539,000+**  
Airports covered: **40** across the **United States**

## 🎯 Objectives  
- Analyze delay trends by **airport**, **airline**, **day**, and **time of day**  
- Predict **when and where** delays are most likely to occur  
- Identify the **top contributing factors** to flight delays  
- Visualize insights for operational decision-making

## 🧪 Methodology  
### 1. Data Preparation  
- Cleaning missing or incorrect values  
- Encoding categorical features (airports, airlines, etc.)  
- Scaling numeric variables as needed  

### 2. Exploratory Data Analysis  
Key analyses include:  
- Distribution of delays  
- Delay frequency across airlines  
- Airport congestion patterns  
- Time-of-day and day-of-week trends  
- Relationship between flight duration and delay

### 3. Modeling  
Predictive models used include:  
- Regression
  
Evaluation metrics:  
- Accuracy  
- Precision & Recall  
- ROC-AUC  
- Feature importance rankings  

### 4. Feature Importance  
We examine which factors most influence delay likelihood, such as:  
- Busy vs. low-traffic airports  
- Airline operational performance  
- Time-of-day congestion  
- Day-of-week travel surges  
- Flight duration effects  

## 📈 Key Insights  
*(Replace or update based on your findings)*  
- Some airports consistently show higher delay rates.  
- Evening flights are more delay-prone than early mornings.  
- Airline choice significantly influences delay likelihood.  
- Certain days show predictable congestion spikes.  
- Longer routes show moderate correlation with delays.

## 🛠️ Tech Stack  
- **ElasticSearch/ElasticCloud**  
- **Kibana**

## [📂 DATASET USED]
(https://www.kaggle.com/datasets/jimschacko/airlines-dataset-to-predict-a-delay/data)
