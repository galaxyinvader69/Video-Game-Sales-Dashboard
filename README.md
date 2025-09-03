# 🎮 Dynamic Video Game Sales Analysis  

## 📌 Project Overview  
This project demonstrates the design and implementation of an end-to-end data analytics solution using the Video Game Sales dataset.
The solution covers the complete lifecycle of a data project — from data acquisition and preparation to data modeling, visualization, and insight generation in Power BI.

Key aspects include:

- *Data Engineering*: Ingested raw CSV data, cleaned missing values, standardized fields (Year, Publisher, Platform), and optimized the dataset for reporting.

- *Data Modeling*: Designed a star-schema style model in Power BI with fact and dimension tables to ensure scalable and efficient analysis.

- *Analytics & KPIs*: Created measures in DAX (e.g., Global Sales) and built dynamic rankings for games and publishers.

- *Visualization*: Developed an interactive dashboard that allows business users to filter by Year and Genre, instantly updating all charts, tables, and KPIs.

- *Business Impact*: Provides actionable insights into market trends, regional preferences, and top-performing products/publishers — supporting strategic decision-making.

- This end-to-end approach mirrors how a real-world organization like Hilti would leverage data — turning raw datasets into business intelligence assets that enable informed decisions at scale.  

---

## 📊 Dataset  
- Source: [Kaggle – Video Game Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales)  
- Records: **16,598**  
- Columns: **11**  

### Key Variables  
- **Rank** – Global sales ranking of the game  
- **Name** – Game title  
- **Platform** – Console/platform (PS4, PC, etc.)  
- **Year** – Year of release  
- **Genre** – Game genre  
- **Publisher** – Publishing company  
- **NA_Sales** – Sales in North America (millions)  
- **EU_Sales** – Sales in Europe (millions)  
- **JP_Sales** – Sales in Japan (millions)  
- **Other_Sales** – Sales in rest of the world (millions)  
- **Global_Sales** – Total worldwide sales (millions)  

---

## ⚙️ Tools Used  
- **Power BI** – Dashboard development and visualization  
- **GitHub** – Version control and project documentation  

---

## 📂 Repository Structure  

📁 Video-Game-Sales-Analysis

┣ 📄 README.md

┣ 📄 vgsales.csv # Dataset

┣ 📄 Video Game Sales Analysis.pbix # Power BI dashboard file

---

## 🚀 Dashboard Features  
- **Dynamic Filters**: Year range and Genre slicers  
- **KPI Cards**: Global Sales (in millions) with dynamic updates  
- **Stacked Area Chart**: Video game sales by region over time  
- **Top 10 Games**: Best-selling titles within selected filters  
- **Top 5 Publishers**: Leading publishers by sales  
- **Regional Breakdown**: Platform-specific sales across NA, EU, JP, and Others  

---

## 📸 Dashboard Preview  
<img width="1768" height="993" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/b42d2d84-f326-4cef-b538-c401d14a70e5" />

---

## 💼 Business Impact  
The **Video Game Sales Analytics Dashboard** demonstrates how raw data can be transformed into actionable business intelligence. By applying this approach in a real-world enterprise (such as Hilti), the solution highlights the following impacts:  

- **Data-Driven Decisions**: Empowers stakeholders to explore sales performance by time, region, or product category, supporting strategic decisions.  
- **Market Insights**: Identifies trends in customer preferences across geographies and timeframes, helping organizations target the right markets.  
- **Performance Tracking**: Highlights top-performing products and publishers (analogous to Hilti tracking best-selling tools or solutions).  
- **Scalability**: The architecture can be extended to include live data sources, enabling real-time analytics for continuous monitoring.  
- **Efficiency**: Replaces static reports with interactive dashboards, reducing manual effort and accelerating business reviews.   

---

## 🏁 Conclusion  
This project demonstrates how a raw dataset can be transformed into a **dynamic and interactive analytics solution** using Power BI.  
By building an **end-to-end architecture** — from data ingestion and modeling to visualization and KPI reporting — the project highlights both technical and business-facing capabilities.  

Key takeaways include:  
- The importance of **data cleaning and modeling** for reliable insights.  
- The role of **DAX measures and slicers** in enabling real-time interactivity.  
- The value of **dynamic dashboards** for monitoring trends, performance, and market opportunities.  

This end-to-end solution proves the ability to convert raw data into **business intelligence assets** that support **data-driven decision-making** and create measurable business impact.  
