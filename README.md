# 📊 Netflix Dataset - Exploratory Data Analysis (EDA)

---

## 🔹 Problem Statement
The objective of this project is to perform **Exploratory Data Analysis (EDA)** on the Netflix dataset to identify patterns, trends, and insights related to content available on the platform.

The analysis focuses on:
- Content distribution  
- Audience targeting  
- Growth trends over time  

---

## 🔹 Dataset Details

- **Dataset Name:** Netflix Titles Dataset  
- **Total Records:** 7787  

### 📁 Features Included
- `show_id` → Unique identifier for each title  
- `type` → Movie or TV Show  
- `title` → Name of the content  
- `director` → Director of the content  
- `cast` → Actors involved  
- `country` → Country of production  
- `date_added` → Date when added to Netflix  
- `release_year` → Year of release  
- `rating` → Content rating (e.g., TV-MA, PG-13)  
- `duration` → Length of movie or number of seasons  
- `genres` → Categories/genres of content  
- `description` → Brief summary  

### 📌 Data Characteristics
- Mostly **categorical data**  
- Contains **missing values** (especially in director, cast, and country)  

---

## 🔹 Approach

The EDA process was carried out in the following steps:

### 1️⃣ Data Understanding
- Examined dataset structure, columns, and data types  

### 2️⃣ Data Cleaning
- Handled missing values by replacing with `"Unknown"`  
- Converted date fields into proper format  
- Extracted `year_added` for trend analysis  

### 3️⃣ Summary Statistics
- Analyzed distribution of categorical variables  
- Checked counts of Movies vs TV Shows  
- Identified most frequent ratings and countries  

### 4️⃣ Univariate Analysis
Studied individual features such as:
- Content type distribution  
- Ratings distribution  
- Genre popularity  

### 5️⃣ Trend Analysis
- Analyzed content addition over the years  
- Observed Netflix growth patterns  

### 6️⃣ Bivariate Analysis
Compared relationships between:
- Type vs Rating  
- Country vs Content count  

### 7️⃣ Visualization
Used:
- 📊 Bar charts → category comparison  
- 📈 Line charts → trend analysis  

---

## 🔹 Results / Insights

- 🎬 Netflix has significantly more **Movies (5377)** than **TV Shows (2410)**  
- 📈 Content growth increased rapidly after **2017**  
- 🌍 **United States** is the leading content producer, followed by **India**  
- 🔞 Most content is rated **TV-MA and TV-14** → focus on adult & young audience  

### 🎭 Popular Genres
- Documentaries  
- Stand-Up Comedy  
- Drama & International Movies  

### 📌 Additional Observations
- Dataset contains mostly **unique entries**  
- Missing values exist in some columns  
- Netflix shows a **strong global presence**  

---

## 🚀 Future Improvements
- Add more advanced visualizations  
- Perform sentiment analysis on descriptions  
- Build recommendation system  

---

## 📌 Conclusion
This analysis provides insights into Netflix’s content strategy, audience preferences, and global expansion trends.
