# LEGO Toy Store Performance Analysis Dashboard

### Developed by *Anand Cinenkanolu*

This repository contains a Power BI project built using the **Maven Analytics LEGO dataset**.  
The dashboard explores LEGO toy store performance across products, themes, prices, and age groups, with the goal of turning a playful dataset into clear, business-ready insights.

This project focuses on **decision-making**, not decoration.

---

## 🎯 Project Goal

Imagine you are running a LEGO toy store.

You have:
- Thousands of LEGO sets  
- Multiple themes and age groups  
- A wide range of prices and piece counts  

The real questions are:
- Which LEGO sets offer the best value?
- What themes actually drive revenue?
- Which products should be stocked more?
- How do price, age, and pieces influence performance?

The goal of this project is to answer those questions using data, not guesswork.

---

## 🛠️ Tools & Technologies

- Power BI Desktop  
- Power Query for data cleaning and transformation  
- DAX for calculated measures and KPIs  
- Star-schema data modeling  
- Maven Analytics LEGO Dataset (CSV)  
- Interactive visuals and slicers  

---

## 📂 Dataset Overview

- LEGO sets released between **1970 and 2022**
- ~18,000+ records after cleaning
- Key fields include:
  - Theme
  - Year
  - Price
  - Pieces
  - Age
  - Product image URL

---

## 🔍 How the Project Was Built

### 1. Data Preparation (Power Query)

- Loaded the raw LEGO dataset  
- Removed unnecessary fields such as URLs and unused metadata  
- Filtered out records with missing price, age, or pieces  
- Fixed data types and formatting issues  
- Created calculated columns for:
  - Age Range (1–4, 5–9, 10–17, 18+)  
  - Price Range ($, $$, $$$, $$$$)

Clean data made everything else possible.

---

### 2. Data Modeling

- Designed a clean **star-schema model**
- Built relationships between:
  - LEGO Sets
  - Themes
  - Calendar table
- Ensured:
  - One-to-many relationships
  - Single-direction filtering
  - No circular dependencies
- Hid technical columns from report view

This reinforced a key lesson:
**Good dashboards are built in the model, not the visuals.**

---

### 3. DAX Measures

Created core measures to drive insights, including:
- Total LEGO Sets
- Average Price per Set
- Average Pieces per Set
- Revenue and value-based comparisons
- Theme-level and product-level performance

DAX felt confusing at first.
Then it clicked.

---

## 📊 Dashboard Overview

This project contains **one interactive report page** focused on usability and clarity.
> Dashboard Overview
![Dashboard Overview](https://github.com/Anand-Cinenkanolu/LEGO-Toy-Store-Performance-Analysis-Dashboard/blob/main/LEGO/Overview.png)


> Set Explorer view
![Set Explorer view](https://github.com/Anand-Cinenkanolu/LEGO-Toy-Store-Performance-Analysis-Dashboard/blob/main/LEGO/Set%20Explorer.png)
### Key Features

- KPI cards for quick overview
- Theme and age-based slicers
- Numeric price range filtering
- Detailed product tables
- Image cards that display LEGO set images dynamically
- Decomposition Tree for drilling from themes down to individual sets
- Bookmarks for reset and navigation

Not flashy.
Just effective.

---

## 🔥 Key Insights

- Certain LEGO themes generate high revenue with fewer products  
- Low-priced sets often drive high volume  
- Premium sets sell less frequently but deliver strong margins  
- Popular themes are not always profitable  
- Value is not just about price, but price *per piece*

Data has no favorites.
It just tells the truth.

---

## 📚 What I Learned

- Data cleaning is most of the work
- Strong data models simplify everything else
- DAX rewards patience, not shortcuts
- Dashboards should answer questions, not impress people
- Learning sticks better when curiosity leads the way

This project didn’t just improve my Power BI skills.
It changed how I think about analytics.

---

## 🔗 Live Dashboard

**Power BI Live Dashboard:**  
[View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNmQ2MGNkMzAtM2I5Ni00NWQ0LWEzYTgtNGNjOGE2NDg2ZDk2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## 📣 Credits

- Dataset & project guidance: **Maven Analytics**
- Special thanks to **Chris Dutton** for creating hands-on, real-world analytics projects

---

## 📬 Contact

For feedback, collaboration, or analytics discussions:

- 📧 [**Email**](anandcinenkanolu@gmail.com)
- 💼 [**LinkedIn**](https://www.linkedin.com/in/Anand-Cinenkanolu/)
- 🗂️ [**Portfolio**](https://codebasics.io/portfolio/Anand-Cinenkanolu)

---

If learning analytics felt this fun all the time, more people would stick with it.
