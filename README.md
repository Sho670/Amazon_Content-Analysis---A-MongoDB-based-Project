# Amazon_Content-Analysis---A-MongoDB-based-Project

This project focuses on analyzing an OTT (Over-The-Top) platform dataset using MongoDB. The aim is to perform data cleaning, transformation, and exploratory data analysis to extract meaningful insights about content trends, genres, ratings, and distribution.

The project is implemented using MongoDB and MongoDB Compass, leveraging aggregation pipelines for advanced querying and analysis.

--- 

📌 Overview

With the rapid growth of OTT platforms like Netflix, Amazon Prime, and Disney+, massive amounts of content data are generated every day. This project leverages the power of MongoDB and MongoDB Compass to perform in-depth data analysis on an OTT dataset.

The goal is simple:

➡️ Extract insights

➡️ Identify trends

➡️ Visualize content distribution


---


# Objectives

The major objectives of this project are:

- Store company sales data in MongoDB collections.
- Perform data cleaning and preprocessing.
- Analyze revenue, profit, and sales performance.
- Generate business insights using MongoDB aggregation.
- Visualize trends and key performance indicators (KPIs).
- Integrate MongoDB for advanced analysis.

---

# Technologies Used

| Technology | Purpose |
|---|---|
| MongoDB | NoSQL database storage |
| Microsoft Power BI | Visualization |
| Jupyter Notebook | Development environment |

---


🚀 Key Features

✨ Data ingestion using MongoDB Compass

✨ Efficient NoSQL schema design

✨ Advanced Aggregation Pipelines

✨ Genre-based analysis

✨ Year-wise content trends

✨ Movies vs TV Shows comparison

✨ Interactive visualizations (Compass Charts)


---


   
📂 Dataset
This project uses an OTT dataset containing:

Title

Genre

Release Year

Type (Movie / TV Show)

Country

Ratings

📁 Format: CSV / JSON
📊 Source: Public datasets (e.g., Kaggle OTT datasets)


---


---


# System Workflow

The project follows the below workflow:

```text
Dataset Collection
        ↓
Data Cleaning & Preprocessing
        ↓
Import Data into MongoDB
        ↓
MongoDB Aggregation Queries
        ↓
Data Visualization
        ↓
Business Insights & Reporting
```

---

# MongoDB Database Structure

The project uses a MongoDB database named:

```bash
companyDB
```

Main collection:

```bash
sales
```

Example MongoDB document:

```json
{
  "order_id": 101,
  "date": "2025-01-15",
  "customer": "ABC Pvt Ltd",
  "region": "South",
  "product": "Laptop",
  "quantity": 5,
  "unit_price": 50000,
  "revenue": 250000,
  "profit": 40000
}
```

---


# Project Workflow

```text
+----------------------+
|   Sales Dataset      |
| (CSV / Excel / JSON) |
+----------+-----------+
           |
           v
+----------------------+
| Data Cleaning &      |
| Preprocessing        |
+----------+-----------+
           |
           v
+----------------------+
| MongoDB Database     |
|  companyDB           |
|  sales collection    |
+----------+-----------+
           |
           v
+----------------------+
| MongoDB Aggregation  |
| Queries & Analysis   |
+----------+-----------+
           |
           v
+----------------------+
| Data Visualization   |
| (Microsoft Power BI) |
+----------+-----------+
           |
           v
+----------------------+
| Business Insights &  |
| Final Reports        |
+----------------------+
```

---

# Project Architecture

```text
                     +----------------------+
                     |   User / Analyst     |
                     +----------+-----------+
                                |
                                v
                     +----------------------+
                     |MongoDB Compass App.  |
                     |  (Analysis Scripts)  |
                     +----------+-----------+
                                |
                +---------------+---------------+
                |                               |
                v                               v
     +----------------------+       +----------------------+
     |      MongoDB         |       |  Visualization Tools |
     |      companyDB       |       |   Microsoft Power BI |
     |  sales collection    |       +----------------------+
     +----------+-----------+
                |
                v
     +----------------------+
     |   Sales Dataset      |
     | CSV / Excel / JSON   |
     +----------------------+
```

---



# Simple Workflow Explanation

1. The sales dataset is collected in CSV, Excel, or JSON format.
2. Data cleaning and preprocessing are performed to remove errors and missing values.
3. Cleaned data is imported into MongoDB collections.
4. MongoDB aggregation pipelines are used for querying and analysis.
5. Pandas processes and analyzes the retrieved data.
6. Visualization libraries generate charts and reports.
7. Final business insights are obtained from the analysis.


---


🎯 Learning Outcomes

Hands-on experience with NoSQL databases

Mastery of MongoDB Aggregation Framework

Real-world data analysis skills

Data visualization using Compass




---


🤝 Future Improvements

🚀 Build a dashboard using web frameworks

🚀 Integrate real-time OTT data

🚀 Deploy using MongoDB Atlas

🚀 Add recommendation system


---


💡 Why This Project Matters:

This project demonstrates how modern data tools can transform raw datasets into valuable insights — a crucial skill in today’s data-driven world.

---

⭐ Show Your Support
If you found this project helpful:

⭐ Star this repository

🍴 Fork it

📢 Share it

📬 Contact
Feel free to connect for collaboration or feedback!

🔥 “Data is the new oil, but insights are the real fuel.”

