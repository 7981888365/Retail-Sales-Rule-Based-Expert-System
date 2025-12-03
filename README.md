# Retail-Sales-Rule-Based-Expert-System
A Hybrid Expert System Using Rule Based Logic To Classify Retail Sales.

A simple, explainable expert system that analyzes retail sales data and identifies business risks using IF–THEN rules.

🚀 Project Overview

This project implements a Rule-Based Retail Sales Expert System designed to evaluate business performance patterns and classify overall risk into:

Low Risk

Moderate Risk

High Risk

Critical Risk

The system uses transparent IF–THEN logic to detect issues such as sales decline, category underperformance, customer concentration, pricing irregularities, and monthly volatility.
It provides clear explanations for every decision, making the model fully interpretable and ideal for academic or business use.

🎯 Objectives

Analyze retail sales data and extract meaningful performance indicators.

Build an expert system that mimics human decision-making using rule-based logic.

Identify potential business risks early and provide actionable insights.

Deliver an explainable, easy-to-understand AI system without using machine learning.

🧠 Key Features

✔️ IF–THEN rule engine

✔️ Categorizes risk into 4 meaningful levels

✔️ Generates human-readable explanations

✔️ Calculates diagnostics (monthly sales, category share, volatility, etc.)

✔️ Detects customer concentration risks

✔️ Identifies sales drops and pricing issues

✔️ Easily expandable knowledge base

🛠️ Tech Stack

Python

Pandas

Rule-Based Reasoning

📂 Project Structure
Retail-Sales-Expert-System/
│
├── retail_risk_screener.py   # Main rule-based expert system
├── data/
│   └── retail_sales_dataset.csv
├── README.md                 # Documentation
└── examples/
    └── sample_inputs.json

🔍 How It Works

Load the retail sales dataset.

Compute key metrics such as:

Monthly sales

Category revenue share

Customer concentration

Price vs quantity

Sales volatility

Apply prioritized IF–THEN rules (Critical → Low).

Output:

Risk level

Rule explanations

Diagnostic metrics

Example Output:

Risk Level: HIGH RISK
Explanation:
 - Recent 3-month revenue dropped 35% vs previous period
 - Customer concentration above safe threshold

📌 Why This Project?

Retail businesses depend on consistent sales performance.
By converting business logic into clear IF–THEN rules, this project shows how expert systems can provide:

Early risk detection

Transparent decision-making

Actionable insights

Practical real-world value

It is an ideal project for learning AI concepts without using black-box models.

🧩 Future Improvements

Add machine learning to forecast future sales.

Build a dashboard for real-time trend monitoring.

Include inventory, promotions, and customer satisfaction data.

Expand knowledge base with more business scenarios.

Deploy as a web or mobile application.

🏁 Conclusion

The Retail Sales Risk Screener demonstrates how expert systems can transform raw sales data into meaningful insights using clear logical rules.
It provides a transparent, interpretable approach to retail analytics and serves as a strong foundation for more advanced decision-support tools.
