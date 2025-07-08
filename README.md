#  🥑 Avocado Retailing Analysis

An end-to-end data analytics project exploring retail trends in the U.S. avocado market using descriptive, predictive, and prescriptive analytics. This project combines EDA, forecasting models, and optimization techniques to generate actionable business insights.

## Table of Contents

- [Overview](#overview)
- [Project Highlights](#project-highlights)
- [Tools & Techniques](#tools--techniques)
- - [Data Preprocessing & EDA](#data-preprocessing--eda)
- [Dataset](#dataset)
- - [Modeling](#modeling)
- [Results](#results)
- [Results](#results)
- [Supplementary Documents](#supplementary-documents)
- [Summary](#summary)
- [How to Run](#how-to-run)
- [Contact](#contact)


📈 Overview
This project investigates the retail market for avocados in the U.S., analyzing trends, forecasting sales, and optimizing supply strategies. Using USDA retail data and historical sales, the analysis covers price fluctuations, consumer preferences, and supply chain decisions.

Key Objectives:

Understand regional sales trends and price dynamics

Forecast future demand for small/medium Hass avocados

Optimize domestic vs. imported supply proportions to minimize costs

📊 Dataset
Sources:

USDA Market News Portal

Kaggle - Augmented Avocado Dataset

Features Include:

Region, Product Type, Average Price, Volume Sold

Organic vs. Conventional classification

Date of Sale, Bag Size, Variety

📁 Download Data CSV
📁 USDA Data XLSX

🔎 Data Preprocessing & EDA
Cleaned missing and inconsistent entries

Categorized regions, product types, and sales channels

Exploratory Analysis:

Seasonal price and volume trends

Regional differences in prices and demand

Correlation between bag size and price

📓 View Jupyter Notebook

🤖 Modeling & Forecasting
Descriptive Analysis:

Violin plots and heatmaps to visualize price/volume differences by region

Highlighted higher average prices in New York vs. higher volumes in Los Angeles

Predictive Forecasting:

Modeled small/medium Hass avocado sales in New York, Seattle, and Los Angeles

Identified seasonal spikes (summer peaks) and upward trends

Used time series forecasting to project next-year sales

🧮 Optimization & Simulation
Developed a Linear Programming model to minimize supply costs

Decision Variables: Proportion of domestic vs. imported supply

Constraints: Demand fulfillment, maintaining 90% imported / 10% domestic mix

Simulation demonstrated cost advantages of imports and recommended regional strategies

✅ Results & Recommendations
Insights:

Imported avocados dominate U.S. supply (86.8%) due to cost stability

Domestic production shows potential in the Midwest if costs are reduced

Sales forecast suggests growing demand, especially in Los Angeles

Seasonal price trends call for demand-aligned inventory planning

Recommendations:

Strengthen imported supply chains, especially in Northeast/Southeast

Invest in reducing domestic production costs

Tailor marketing to regional preferences

Develop pre-made, ready-to-eat avocado products

Enhance e-commerce channels for consumer access

📄 Supplementary Documents
📊 Presentation Slides (PPTX)
📄 Final Report (PDF)

Documents are shared as view-only to maintain integrity and prevent edits.

🗂️ How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/YOURUSERNAME/Avocado-Retailing-Analysis.git
cd Avocado-Retailing-Analysis
(Optional) Create and activate a virtual environment:

bash
Copy
Edit
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Launch the notebook:

bash
Copy
Edit
jupyter notebook Avocado_Retailing.ipynb
🤝 Contact
For inquiries, feedback, or professional connections:

LinkedIn

GitHub

Email

✨ Thank you for exploring this project! Feel free to fork, star, or open issues. Let’s collaborate to drive better data-driven decisions in retail analytics.
