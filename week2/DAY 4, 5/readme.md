## Movie Analytics & User Behavior Analysis using Databricks
## Project Overview

This project focuses on building an end-to-end data engineering pipeline using Databricks to analyze movie data and understand user behavior.

The dataset contains information about movies, user ratings, and tags. Since this data is stored in separate files, it is difficult to analyze directly. This project integrates and processes the data to generate meaningful insights such as popular genres, user activity, and rating trends.

## Business Problem

In streaming platforms, data like ratings, tags, and user interactions are stored in separate sources, making it difficult to analyze user preferences and content performance.

This project solves this problem by combining and transforming the data to provide insights that help:

- Understand user behavior
- Identify trending content
- Support better decision-making

## Dataset
- Source: MovieLens Dataset (Kaggle)

## Tables Used:

- movies → movie details (title, genres)
- ratings → user ratings for movies
- tags → user-generated tags
- links → external movie IDs

## Architecture
This project follows the Medallion Architecture:

```Bronze Layer``` → Raw data ingestion

```Silver Layer``` → Data cleaning and transformation

```Gold Layer``` → Aggregated insights

## Technologies Used
- Databricks
- PySpark
- SQL
- Delta Lake
- Databricks SQL Dashboard
- Data Pipeline Flow
- Load raw CSV files into Bronze layer
- Clean and transform data in Silver layer
- Join datasets using movieId and userId
- Perform aggregations for insights
- Store results in Gold layer
- Create dashboard for visualization

## Key Insights

Popular genres (Drama, Comedy, Action)

High-rated movies (quality content)

User activity patterns

Rating trends over time

## Dashboard
An interactive dashboard is created using Databricks SQL to visualize:

- Genre popularity
- User activity funnel
- Rating trends
- High-rated content

## Results

Dashboard1_1776661178070.png Dashboard2_1776661229396.png

👥 Team - Datalyth

P. Praveena

S. Naga Chaitanya

N. Harsha
