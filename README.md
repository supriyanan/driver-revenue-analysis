# Data Analysis for Maximizing Revenue for Cab Drivers using Python
## Project Overview
In the rapidly growing taxi service industry, increasing driver income is crucial for long-term sustainability and satisfaction. This project analyzes whether the passenger payment type has an impact on the total fare amount. By examining the relationship between payment methods and fare values, the study aims to generate insights that can help taxi drivers maximize their revenue.

## 🛠 Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Statistical Hypothesis Testing

## Objective
This project aims to examine whether the total fare of a taxi ride depends on the payment method (cash or credit card). Using Python, basic statistical analysis, and hypothesis testing, the study evaluates whether there is a significant difference in fare amounts between the two payment types. The goal is to provide insights that can help taxi drivers understand if certain payment methods lead to higher revenue.

## Research Questions
- Is there a relationship between the total fare amount and the payment method used?
- Can encouraging specific payment methods help drivers increase earnings without negatively impacting customer experience?

---

## 📊 Dataset
The dataset contains taxi trip records used to analyze fare differences based on payment method.

**Key columns used in analysis:**
- payment_type
- fare_amount
- trip_distance
- passenger_count
- Airport_fee
   
**New features created:**
- trip_duration    

---
## 🔍 Analysis Workflow
- Data loading and initial inspection
- Data cleaning and preprocessing
- Feature engineering (trip duration calculation)
- Exploratory data analysis (EDA)
- Hypothesis testing to compare fare amounts by payment method

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
