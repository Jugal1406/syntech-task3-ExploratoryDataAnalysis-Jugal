# syntech-task3-ExploratoryDataAnalysis-Jugal
🔹 Problem Statement

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Netflix dataset to identify patterns, trends, and insights related to content available on the platform. The analysis focuses on understanding content distribution, audience targeting, and growth trends over time.

🔹 Dataset Details
Dataset Name: Netflix Titles Dataset
Total Records: 7787
Features Included:
show_id: Unique identifier for each title
type: Movie or TV Show
title: Name of the content
director: Director of the content
cast: Actors involved
country: Country of production
date_added: Date when added to Netflix
release_year: Year of release
rating: Content rating (e.g., TV-MA, PG-13)
duration: Length of movie or number of seasons
genres: Categories/genres of content
description: Brief summary
Data Characteristics:
Mostly categorical data
Some missing values (especially in director, cast, and country)
🔹 Approach

The EDA process was carried out in the following steps:

Data Understanding
Examined dataset structure, columns, and data types
Data Cleaning
Handled missing values by replacing with "Unknown"
Converted date fields into proper format
Extracted year from date_added for trend analysis
Summary Statistics
Analyzed distribution of categorical variables
Checked counts of Movies vs TV Shows
Identified most frequent ratings and countries
Univariate Analysis
Studied individual features such as:
Content type distribution
Ratings distribution
Genre popularity
Trend Analysis
Analyzed content addition over the years
Observed growth patterns of Netflix
Bivariate Analysis
Compared relationships between:
Type vs Rating
Country vs Content count
Visualization
Used bar charts and line graphs to represent:
Content distribution
Yearly trends
Genre popularity
🔹 Results / Insights
Netflix has significantly more Movies (5377) than TV Shows (2410)
Content growth increased rapidly after 2017, indicating platform expansion
United States is the leading content producer, followed by India
Most content is rated TV-MA and TV-14, showing focus on adult and young audiences
Popular genres include:
Documentaries
Stand-Up Comedy
Drama & International Movies
Dataset is mostly clean with unique entries, but has missing values in some fields
Netflix content reflects a global presence with contributions from multiple countries
