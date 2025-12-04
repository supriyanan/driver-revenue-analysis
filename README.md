# Maximizing Revenue for Cab Drivers

## Project Overview
This project analyzes cab trip data to understand how drivers can increase their revenue.  
The analysis focuses on distance, fare, tips, peak hours, and factors that affect total earnings.

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
