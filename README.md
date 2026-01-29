# Blinkit Sales Analysis Dashboard

## Dashboard Preview
![Dashboard Screenshot] <img width="1052" height="540" alt="image" src="https://github.com/user-attachments/assets/c052d5a6-cf59-4b26-bd70-c108808dba4c" />
## Project Overview
This Power BI dashboard provides an end-to-end analysis of **Blinkit's** retail data. By transforming raw data into interactive visuals, the dashboard helps stakeholders understand which factors (like outlet size or product type) drive the most revenue and where customer satisfaction is highest.
## Key Features & Insights
* **Total Revenue:** The platform achieved **$1.2M** in total sales with an average customer rating of **3.9**.
* **Top Categories:** **Fruits & Vegetables** and **Snack Foods** are the leading item types by count, both exceeding 1,200 items.
* **Growth Trends:** Sales saw a significant peak in **2018**, reaching **$205K**, followed by stabilization through 2022.
* **Outlet Performance:** * **Tier 3** locations lead in sales volume (**$472.13K**).
    * **Medium-sized** outlets contribute the largest share of revenue (**$507.9K**).
    * **Supermarket Type 1** is the dominant outlet type, generating **$787.5K** in sales.
## Technical Workflow
### 1. Data Cleaning
Used **Power Query** to standardize "Fat Content" labels (fixing inconsistent naming conventions) and handled null values in the "Outlet Size" column to ensure data integrity.
### 2. DAX Development
Created custom measures for **Total Sales, Avg Sales, Item Count, and Avg Rating** to ensure dynamic filtering and accurate calculations across all visuals.
### 3. UI/UX Design
Implemented a sleek sidebar navigation for slicers (**Location, Size, Item Type**) and utilized a "High-Value" color scheme to enhance readability and user engagement.

## Files in this Repository

| File | Description |
| :--- | :--- |
| **Blinkit Analysis.pbix** | The core Power BI project file. |
| **Blinkit_Data.csv** | The raw dataset used for the analysis. |
| **Business_Requirements.md** | Detailed documentation of project goals and KPIs. |
