# 🏡 Data Mining for Housing Market Segmentation in Melbourne
### IS466 – Decision Support Systems  
### King Saud University  
### Group Project  

This project applies the CRISP-DM framework to perform **market segmentation** on the Melbourne Housing Market dataset.  
Using the **K-Prototypes** clustering algorithm, we identify meaningful groups of properties based on numerical and categorical features.

---

## 📌 Project Overview

Real-estate markets contain diverse types of properties that vary in price, size, structure, and location.  
Understanding these variations helps stakeholders—such as investors, developers, and agencies—make informed decisions.

Our goal is to use **data mining techniques** to discover natural market segments within Melbourne’s housing market.

---

## 📊 Objectives

### **Business Objective**
Identify meaningful property segments (e.g., premium homes, standard family houses, compact/affordable units) to support pricing, marketing, and investment decisions.

### **Data Mining Objective**
Apply a clustering method capable of handling mixed numeric and categorical data to reveal natural groupings in the housing market.  
The **K-Prototypes** algorithm is used due to the presence of both:

- Numerical features (e.g., price, landsize, rooms)  
- Categorical features (e.g., type, regionname)

---

## 🗂 Dataset Information

- **Source:** Kaggle — Melbourne Housing Market  
- **Records:** ~34,000 property sales  
- **Features:** Price, Rooms, Bathroom, Car, Landsize, BuildingArea, Distance, Type, Regionname, Coordinates  
- **Format:** CSV  

The dataset contains missing values and outliers, which are handled during preprocessing.

---

## 🔧 Tools & Technologies

- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **Matplotlib, Seaborn**
- **kmodes / K-Prototypes library**
- **Jupyter Notebook**

---

## 🔄 CRISP-DM Process Summary

### **1. Business Understanding**
Defined business and data-mining objectives focused on discovering market structure using clustering.

### **2. Data Understanding**
Explored dataset shape, missing values, distributions, and categorical uniqueness.

### **3. Data Preparation**
Performed:
- Column selection  
- Outlier removal  
- Median imputation  
- Dropping unnecessary features  
- Handling missing coordinates  
- Final validation of data quality  

### **4. Modeling**
Applied **K-Prototypes** with:
- Scaled numerical features  
- Original categorical features (no encoding needed)  
- Final model chosen with **k = 3** clusters  

### **5. Evaluation**
Used:
- **Silhouette score (Gower distance)**  
- Cluster statistics  
- Visualization of cluster separation  
- Segment interpretation  

### **6. Deployment**
Project deployed via GitHub including:
- Cleaned dataset  
- Notebook with full workflow  
- Visualization outputs  
- Final segmentation results  

---

## 🎯 Final Segments Summary

### **Segment 2 — Premium (S-Tier)**
- Highest price  
- Large land & building areas  
- Mostly metropolitan  
- Majority houses  

### **Segment 1 — Family Homes (A-Tier)**
- Moderate prices  
- Large land size  
- Predominantly houses  

### **Segment 0 — Affordable/Compact (B-Tier)**
- Lowest price  
- Smallest areas  
- High percentage of units  

These segments provide actionable insights for investors and agencies.

---

## 📈 Visualizations Included
- Cluster count bar chart  
- Price distribution by tier (boxplot)  
- Price vs Distance (colored by segment)  
- PCA-based cluster visualization (optional)  
- Numeric summary tables for each cluster and tier  

---

## 📤 Exported Files
- `Melbourne_Final_Segmentation.csv`  
- Cleaned dataset ready for further analysis  
- Notebook with all CRISP-DM stages  
- Model outputs + plots  

---

## 👥 Team Members
- Mohammed Aljallal – 442170177  
- Abdullah Alshammari – 443100803  

Supervisor: **Prof. Abdulrahman Merza**

---

## 📬 Contact
For inquiries or reuse, feel free to open an issue or contact the team.

---

## ⭐ Project Status
This project is completed for academic demonstration.  
No ongoing maintenance or updates are planned.
