# **Real Estate Price Prediction Analysis**

## **Project Overview**  
This project aims to analyze historical real estate pricing data to predict future price trends based on factors such as location, square footage, and market conditions. Using data scraping, cleaning, and visualization techniques, the goal is to uncover actionable insights that guide investment decisions and understand market behavior.  

---

## **Table of Contents**  
1. [Introduction](#introduction)  
2. [Tech Stack](#tech-stack)  
3. [Data Sources](#data-sources)  
4. [Project Workflow](#project-workflow)  
5. [Insights & Findings](#insights--findings)  
6. [How to View the Project](#how-to-run-the-project)  
7. [Contact](#contact)  

---

## **Introduction**  
Real estate prices are influenced by multiple factors, including location, property size, and economic conditions..  

---

## **Tech Stack**  
- **Programming Languages**: Python  
- **Libraries/Tools**:  
  - Data Scraping: `BeautifulSoup`, `Selenium`  
  - Data Cleaning & Analysis: `Pandas`, `NumPy`  
  - Data Visualization: `Matplotlib`, `Seaborn`, `Power BI`  

---

## **Data Sources**  
The data is sourced through web scraping from real estate platforms like:  
1. [squareyards.com](https://www.squareyards.com/?source=fyEmgc3%2FD3F2sUtf6c4d6Q%3D%3D0n&gclid=Cj0KCQiAouG5BhDBARIsAOc08RTXCl6_3USKv007I7H7A2lHejiH6IdwtJDljlVZBNK09WwVot8PMbcaAmlsEALw_wcB&gad_source=1)

Collected features include:  
- **Property Details**: Location, Size (sq. ft), Price, Type (apartment/house), Amenities, Property Info.  
- **Amenities**: Parking, Pool, Clubhouse, etc.  
- **Market Conditions**: Interest rates, Amenities Impacting Price.  

---

## **Project Workflow**  

### **1. Data Collection**  
- Scraped data using tools like `BeautifulSoup` and `Selenium`.  
- Extracted relevant features: price, location, square footage, amenities.  

### **2. Data Cleaning**  
- Handled missing values using median/mean imputation.  
- Removed outliers with IQR (Interquartile Range) or z-scores.  
- Normalized numerical features to ensure consistent scaling.  

### **3. Data Visualization**  
- **Python**: Used `Matplotlib` and `Seaborn` for scatter plots and bar charts to explore feature correlations.  
- **Power BI**: Created an interactive dashboard to visualize:  
  - Price trends across regions and property types.  
  - Comparative analysis based on amenities.  

---

## **Insights & Findings**  

1. **Location Premium**: Properties in downtown areas are 20-30% costlier than suburban properties.  
2. **Property Size**: Larger properties (>3000 sq. ft) have a premium of 15-25%.  
3. **Market Trends**:  
   - Cities like **Mumbai** and **Delhi** are experiencing consistent price growth due to gentrification.  
5. **Impact of Amenities**:  
   - Properties with pools, clubhouse, or parking spaces can command up to 10% higher prices.  
6. **Economic Factors**: Rising interest rates reduce market activity, negatively affecting home affordability.  

---

## **Dashboard** :
- Use Power BI to open the provided .pbix file for an interactive experience.

## **Dashboard Screenshot** :

## Page 1
![Page 1](https://drive.google.com/uc?export=view&id=1DvAWmHmZPXILaMjlPWzugxd4cayApdfo)

## Page 2
![Page 2](https://drive.google.com/uc?export=view&id=1NfS--DdIR0C_AekDnjyEuU2EU-ebL5xP)

---

## Contact  
For queries or contributions:  

- **Name**: Mayur Lohar, Salil Singh , Ashish Dabas , Mahalaxmi Mareedu , Alpana Sahu 
- **Email**: [loharmayur43@gmail.com](loharmayur43@gmail.com)  
- **GitHub**: [github.com/Mayur313](https://github.com/Mayur313)  
- **LinkedIn**: [https://www.linkedin.com/in/mayur-lohar-8b182732a/](https://www.linkedin.com/in/mayur-lohar-8b182732a/)  
