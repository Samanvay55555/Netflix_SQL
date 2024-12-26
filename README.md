# Netflix_SQL

📊 Netflix Movies and TV Shows Data Analysis using SQL

Welcome to an in-depth analysis of Netflix’s movies and TV shows data using SQL. This project demonstrates advanced SQL queries to uncover insights and trends within the dataset. Below, you’ll find the project goals, dataset details, business questions, and insights.

🎯 Objectives
	1.	Understand the distribution of movies and TV shows.
	2.	Analyze ratings to determine the most common ones for each type of content.
	3.	Explore content trends based on release years, countries, and durations.
	4.	Categorize and filter content using specific criteria and keywords.

📂 Dataset

The dataset for this project is sourced from Kaggle. It includes information about Netflix’s movies and TV shows, such as titles, ratings, release years, countries, and more.

Database Schema

DROP TABLE IF EXISTS netflix;
CREATE TABLE netflix (
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);

❓ Business Questions
	1.	How many movies and TV shows are available on Netflix?
	2.	What are the most common ratings for movies and TV shows?
	3.	What are the movies released in a specific year (e.g., 2020)?
	4.	Which five countries have the most content on Netflix?
	5.	What is the longest movie available on Netflix?
	6.	Which content has been added in the last five years?
	7.	Which movies or TV shows are directed by ‘Rajiv Chilaka’?
	8.	What are the TV shows with more than five seasons?
	9.	How many content items are there in each genre?
	10.	What are the top five years with the highest average content release by India?
	11.	Which movies are categorized as documentaries?
	12.	How many content items lack a director?
	13.	How many movies featuring ‘Salman Khan’ have been released in the last 10 years?
	14.	Who are the top 10 actors with the most appearances in Indian-produced movies?
	15.	How can content be categorized based on keywords like ‘kill’ and ‘violence’?

📈 Key Findings
	•	Content Distribution: Analyzed the number of movies versus TV shows to understand platform content trends.
	•	Popular Ratings: Identified the ratings most frequently assigned to Netflix content.
	•	Geographical Insights: Highlighted the top countries producing Netflix content and their release trends.
	•	Keyword Categorization: Explored how specific terms like “kill” and “violence” impact content classification.

