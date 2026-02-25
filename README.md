# 🏠 Egypt Real Estate Listings Analysis
# 📋 Project Overview
A comprehensive Exploratory Data Analysis (EDA) of the Egyptian real estate market. This project focuses on analyzing property listings across prime locations like El Gouna, New Cairo, and the North Coast to uncover pricing trends, space utilization, and payment structures.

# 🗂️ Data Dictionary
The dataset contains detailed information for each listing
Column Name,Description,Sample Value
Price,Total property price in EGP,"8,000,000"
Location,Project name + City + Governorate,"Swan Lake Gouna, Red Sea"
Type,"Property category (Chalet, Apartment, Villa)",Chalet
Size,Unit area in Square Feet and Square Meters,732 sqft / 68 sqm
Bedrooms,Number of bedrooms (includes maid rooms),1 + Maid
Bathrooms,Number of bathrooms in the unit,1
Available_from,Expected delivery/handover date,31-Aug-25
Payment_method,Payment type (Cash or Installments),Cash
Down_payment,Upfront amount required,"1,200,000 EGP"

# 🚀 Key Objectives
Data Cleaning: Standardizing the size and bedrooms columns from string formats to numerical values for statistical analysis.

Geographical Analysis: Identifying the most expensive real estate hubs and emerging markets in Egypt.

Delivery Trends: Analyzing the correlation between delivery dates (Available_from) and pricing.

Feature Engineering: Extracting "Governorate" and "Project Name" from the location string to enable better grouping.

# 🛠️ Tech Stack
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Environment: Jupyter Notebook

# 📊 Quick Insights
