# 🎬 Movie Analytics Dashboard – Power BI Project

## 📌 Project Overview

This Power BI project analyzes a comprehensive movie dataset to uncover insights related to **box office revenue, IMDb ratings, votes, runtime, genres, directors, and yearly trends**. The dashboard focuses on understanding the relationship between **movie quality (ratings & metascore)** and **commercial success (revenue & votes)** across time and genres.

The project is designed for **data analysis, visualization best practices, and interview-ready storytelling**.

---

## 🎯 Objectives

* Analyze **year-wise trends** in movie releases, revenue, ratings, runtime, and votes
* Identify **top-performing genres, movies, and directors** based on revenue and popularity
* Understand the **relationship between IMDb ratings and box office revenue**
* Study how **runtime, votes, and ratings influence revenue**
* Provide **high-level KPIs** for quick business understanding

---

## 📊 Key Business Questions Answered

### 📅 Time-Based Analysis

* How many movies were released each year?
* What is the trend of total box office revenue over the years?
* How has the average IMDb rating changed year over year?
* What is the average runtime of movies released each year?
* Which year recorded the highest total box office revenue?


### 🎭 Genre & Rating Analysis

* How are movies distributed across different genres?
* Which genres have the highest average IMDb ratings?
* How is total revenue distributed among genres?
* What is the average Metascore for each genre?
* Which genres receive the highest number of votes?

### 🎥 Movie & Director Performance

* Which directors have generated the highest total revenue?
* Which movies received the highest number of votes?
* How does revenue progress from all movies to the top 10 highest-grossing movies?
* What is the relationship between movie revenue and IMDb rating?

### 🔍 Advanced Analytical Insights

* How does yearly revenue get affected by rating, votes, and runtime across genres?
* What is the trend of average revenue and average rating by movie runtime?
* What is the pattern of revenue of each movie by average rating per year?
* How does yearly revenue vary when categorized by genre?

---

## 📈 Visualizations Used

| Analysis Type               | Visualization                |
| --------------------------- | ---------------------------- |
| Year-wise trends            | Line Chart                   |
| Movie count & rankings      | Bar / Column Chart           |
| Revenue distribution        | Treemap / Stacked Area Chart |
| Revenue vs Rating           | Scatter Plot                 |
| Revenue progression         | Funnel Chart                 |
| Multiple metrics comparison | Combo Chart                  |
| Summary metrics             | KPI Cards                    |

> **Note:** Scatter plots use **tooltips and Top-N filtering** as Power BI does not support permanent data labels for bubbles.

---

## 🧮 Key KPIs

* Total Number of Movies Released
* Highest Movie Revenue
* Average Revenue
* Average IMDb Rating
* Average Metascore
* Average Runtime
* Total Votes Cast
* Total Number of Genres
* Most Common Genre
* Unique Actors Count

---

## 🛠 Tools & Technologies

* **Power BI Desktop** – Data modeling & visualization
* **DAX** – Measures and calculated columns
* **Power Query** – Data cleaning and transformation
* **Excel / CSV Dataset** – Source data

---

## 📐 Data Modeling Highlights

* Star schema with **Movies** as the fact table
* Dimension tables for **Genre, Director, Year**
* Runtime binning for grouped analysis
* Top-N filters for performance optimization

---

## 💡 Key Insights (Sample)

* High box office revenue does not always correlate with high IMDb ratings
* Action and Adventure genres consistently dominate revenue across years
* Movies with higher audience votes tend to generate higher revenue than those with only high ratings
* Optimal runtime range exists where both revenue and ratings peak

---

## 📁 Project Structure

```
Movie Analytics Power BI Project
│
├── Dataset/
│   └── movies_data.csv
├── PowerBI_File/
│   └── Movie_Analytics_Dashboard.pbix
├── README.md
```

---

## 🚀 How to Use

1. Open the `.pbix` file in **Power BI Desktop**
2. Refresh data if required
3. Use slicers (Year, Genre, Director) for interactive analysis
4. Hover over visuals to view detailed tooltips

---

## 🎓 Learning Outcomes

* Practical application of **data visualization best practices**
* Strong understanding of **business-driven analytics**
* Hands-on experience with **Power BI, DAX, and dashboard design**
* Ability to explain insights clearly in interviews

---

## 👤 Author

**Gayathri Lanke**
Data Science Aspirant | Power BI & Analytics

---

## 📌 Disclaimer

This project is for **educational and analytical purposes only**. Revenue figures and ratings are based on the provided dataset and may not reflect real-world values.
