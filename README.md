# Data Analysis for Maximizing Revenue for Cab Drivers using Python
## Project Overview
In the rapidly growing taxi service industry, boosting driver income is key to maintaining long-term growth and driver satisfaction. 
This project analyzes whether the payment method used by passengers (Cash vs Credit Card) has any impact on the total fare amount earned by drivers. 
The analysis uses Python-based exploratory data analysis and hypothesis testing to derive actionable insights.

## Problem Statement
Taxi drivers often experience variations in earnings depending on trip characteristics and passenger behavior. 
One important but less explored factor is the payment method used by customers. 
This project aims to determine:
1) Does the total fare amount differ based on payment method?
2) Do credit card payments result in higher fares compared to cash payments?

## Objective
The primary objective of this project is to evaluate whether the total fare of a taxi ride depends on the payment method (Cash vs Credit Card). 
Using Python, basic statistical analysis, and hypothesis testing, the project seeks to identify any significant difference in average fare amounts between the two payment types.

## Research Questions
Is there a statistically significant relationship between payment method and total fare amount?
Can encouraging a particular payment method help drivers increase their revenue without affecting customer experience?

---

## Dataset Details
Main columns used:
- pickup_datetime  
- dropoff_datetime  
- trip_distance  
- fare_amount  
- tip_amount  
- tolls_amount  
- total_amount  

New features created:
- trip_duration  
- pickup_hour  

---

## Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Jupyter Notebook  

---

## Key Insights
- Longer trips give higher revenue  
- Evening hours (6 PM – 11 PM) have highest demand  
- Tips are higher in longer and late-night trips  
- Some pickup zones give better earning opportunities  

---

## How to Run

1. Install libraries:
```
pip install pandas numpy matplotlib seaborn plotly jupyter
```

2. Download the dataset and place it in the project folder.
Example:
```
data/cab_trip_data.csv
```

3. Open Jupyter Notebook:
```
jupyter notebook
```

4. Run the analysis notebook:
```
Cab_Driver_Revenue_Analysis.ipynb
```

## Project Structure
```
project-folder/
│
├── data/
│   └── cab_trip_data.csv
│
├── Cab_Driver_Revenue_Analysis.ipynb
└── README.md
```
