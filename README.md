# 🥑 Avocado Retailing Analysis

An end-to-end data analytics project exploring retail trends in the U.S. avocado market using descriptive, predictive, and prescriptive analytics. This project combines EDA, forecasting models, and optimization techniques to generate actionable business insights.

---

## Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Project Highlights](#project-highlights)
- [Tools & Techniques](#tools--techniques)
- [Dataset](#dataset)
- [Data Preprocessing & EDA](#data-preprocessing--eda)
- [Modeling](#modeling)
- [Results](#results)
- [Recommendations](#recommendations)
- [Supplementary Documents](#supplementary-documents)
- [How to Run](#how-to-run)
- [Contact](#contact)

---

## Overview

This project addresses retail pricing strategy and sales trends in the U.S. avocado market. By applying descriptive, predictive, and prescriptive analytics, it delivers insights to inform pricing, supply chain planning, and marketing decisions.

---

## Objectives

- Analyze historical retail sales data
- Build forecasting models for avocado prices and demand
- Optimize pricing and distribution strategies
- Generate actionable recommendations for retailers

---

## Project Highlights

- Descriptive analytics using EDA and visualization to uncover sales trends
- Predictive analytics with time series forecasting (ARIMA, Prophet)
- Prescriptive analytics for cost optimization and supply recommendations
- Integration of USDA Market News and augmented retail pricing data
- Clear storytelling through notebooks, slides, and reports

---

## Tools & Techniques

- **Languages:** Python (pandas, matplotlib, seaborn, scikit-learn, statsmodels)
- **Notebooks:** Jupyter Notebook
- **Visualization:** matplotlib, seaborn
- **Forecasting:** ARIMA, Facebook Prophet
- **Optimization:** Linear programming

---

## Dataset

- **Sources:** USDA Market News Retail Data, Kaggle Avocado Augmented dataset
- **Government-Verified Source:**
The primary data was obtained from the USDA Market News Portal, a trusted government website known for providing reliable and verified agricultural data.
- **Features Include:**
  - Date
  - Region
  - Average Price
  - Total Volume
  - Hass Avocado Sizes
  - Type (Conventional/Organic)
  - Year

## 🗂️ Dataset

- **Download CSV:** [Avocado USDA Market CSV] (https://github.com/KiruthikaRamadoss/Avocado-Retailing-Analysis/blob/main/avocado-files/Avocado_USDA_data_market.xlsx)

- **Augmented Analysis Dataset:** [Augmented Avocado CSV (Google Drive)](https://drive.google.com/file/d/1VLf6qCnIXdhVRNxmQkVLyoyiHyJL7RVW/view?usp=drive_link)
  
---

## Data Preprocessing & EDA

- Cleaned and merged multiple data sources
- Handled missing values and outliers
- Created time series features for modeling
- Visualized trends in price and volume across regions

**Key Insights:**
- Price differences between organic and conventional avocados
- Seasonal demand peaks during warmer months
- Regional price variations (e.g., New York consistently higher)
- Strong positive correlation between volume and price for certain SKUs

---

## Modeling

- **Forecasting Approaches:**
  - ARIMA for average price trends
  - Facebook Prophet for multi-seasonality
- **Validation:**
  - Train/test split
  - RMSE comparison across models
- **Prescriptive Analytics:**
  - Linear programming optimization to minimize costs
  - Recommendations for balancing imported and domestic supply

📓 *Notebooks:*
- [Descriptive Analysis](Avocado_Retailing_Descriptive_Analysis.ipynb)
- [Predictive Analysis](PredictiveAnalytics-AvocadoRetailing.ipynb)
- [Prescriptive Analysis](Avocado_Retailing_Prescriptive_Analysis.ipynb)

---

## Results

- Accurate forecasting of average avocado prices
- Seasonal peaks clearly identified (higher prices in colder months)
- Optimized supply strategy suggesting heavy reliance on imports with targeted domestic production
- Regional recommendations for pricing and marketing

---

## Recommendations

- **Demand Forecasting:** Use forecasting to align inventory with seasonal demand
- **Product Strategy:** Develop pre-made, ready-to-eat avocado options
- **Market Targeting:** Tailor products to regional preferences (e.g., health-focused in LA)
- **Supply Chain:** Focus on imports while reducing domestic production costs
- **E-commerce:** Build robust online shopping capabilities
- **Risk Management:** Diversify supply sources and monitor geopolitical risks

---

## Supplementary Documents

- 📊 [Presentation Slides (PPTX)](https://github.com/KiruthikaRamadoss/Avocado-Retailing-Analysis/blob/main/avocado-files/AVOCADO%20%20RETAILING%20FINAL.pptx)
- 📄 [Final Project Report (PDF)](https://github.com/KiruthikaRamadoss/Avocado-Retailing-Analysis/blob/main/avocado-files/Avocado%20Retailing%20Project%20Report.pdf)

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/KiruthikaRamadoss/Avocado-Retailing-Analysis.git
   cd Avocado-Retailing-Analysis

2. Create and activate a virtual environment (Optional):
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`

3. Install dependencies:
   pip install -r requirements.txt

4. Launch the notebook:
   jupyter notebook HomeLoan.ipynb

---

## Contact

For inquiries, collaboration, or feedback:

- [LinkedIn](https://www.linkedin.com/in/kiruthikaramadoss/)
- [GitHub](https://github.com/KiruthikaRamadoss)
- [Email](mailto:k_r549@txstate.edu)
