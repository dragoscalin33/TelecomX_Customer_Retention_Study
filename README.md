# 📊 Customer Churn Analysis – Telecom X

## 🧭 Project Overview

This project was developed as part of a Data Science challenge, with one central question in mind: **Why are Telecom X customers leaving?** 

I dove into the data to uncover the key drivers behind customer churn. Beyond just crunching numbers, the goal was to understand customer behavior in depth, and to provide actionable insights that could help reduce churn, improve retention strategies, and ultimately enhance customer satisfaction.

## 🗂 Project Structure

The entire analysis is contained in a single Jupyter Notebook:

- `TelecomX_Churn_Analysis_Report.ipynb`: Includes data loading, cleaning, and processing, as well as the complete exploratory analysis and final conclusions with recommendations.

## 🛠 Tools & Libraries

To carry out the analysis, I used the following Python libraries:

- `pandas` – for data manipulation and transformation.  
- `numpy` – for numerical operations and array handling.  
- `requests` – for retrieving data from external sources.  
- `seaborn` and `matplotlib.pyplot` – for creating clear and visually engaging graphs and charts.

## ▶️ How to Run the Project

If you’d like to explore the analysis on your own machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
   cd YOUR_REPOSITORY

(Replace YOUR_USERNAME and YOUR_REPOSITORY with your actual GitHub username and repo name.)
	2.	(Optional) Create and activate a virtual environment:

python -m venv venv
## On Windows:
.\venv\Scripts\activate
## On macOS/Linux:
source venv/bin/activate


	3.	Install dependencies:

pip install pandas numpy requests seaborn matplotlib


	4.	Open the notebook with Jupyter:

jupyter notebook TelecomX_Churn_Analysis_Report.ipynb

This will launch the notebook in your browser. From there, you can run the cells and walk through the full analysis.

📌 Key Findings

Here are a few of the main insights I discovered:
	•	Customers with shorter tenure are more likely to churn.
	•	Monthly contracts are strongly correlated with high churn rates.
	•	The “Electronic check” payment method is linked to higher churn.
	•	Subscribing to additional services (like online security and technical support) is associated with better customer retention.
	•	Surprisingly, fiber optic customers showed higher churn rates—possibly pointing to issues with service quality or unmet expectations.

💡 Recommendations

Based on the analysis, here are some suggestions that could help reduce churn:
	•	Introduce welcome programs focused on onboarding new customers.
	•	Offer incentives for longer-term contracts.
	•	Investigate issues related to the Electronic check payment method.
	•	Promote value-added services as part of bundled plans.
	•	Reassess fiber service quality and customer support experience.

All the details, graphs, and recommendations can be found in the notebook report.


Author: Dragos Calin
Date: May 24, 2025
