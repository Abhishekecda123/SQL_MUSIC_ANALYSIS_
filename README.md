# SQL_MUSIC_ANALYSIS_
🎵 Music Store Data Analysis - SQL Project
📝 Overview
This project performs an in-depth analysis of a digital music store's database using PostgreSQL. The goal is to answer critical business questions regarding customer behavior, sales performance, and music popularity to help the store optimize its marketing strategies and business growth.

📊 Data
The dataset represents a fictional music store and consists of several interconnected tables.

Tables Used: Employee, Customer, Invoice, InvoiceLine, Track, Album, Artist, and Genre.

Key Metrics: Total sales, track length (milliseconds), customer spending, and genre popularity.

Schema: The data follows a relational structure where invoices are linked to customers, and invoice lines connect tracks to their respective artists and genres.

💡 Solution
The analysis is divided into three levels of complexity to demonstrate different SQL capabilities:

1. Basic Analysis
Focused on foundational data retrieval and sorting:

Seniority Levels: Identified the senior-most employee based on job levels.

Geographical Insights: Ranked countries and cities with the highest number of invoices to identify prime locations for promotional events like music festivals.

Customer Identification: Pinpointed the "Best Customer" based on total spending.

2. Moderate Analysis
Focused on joining multiple tables and filtering data:

Rock Music Listeners: Extracted a list of customers who prefer Rock music to assist in targeted email campaigns.

Top Artists: Identified the top 10 artists who have written the most Rock songs in the dataset.

Average Track Length: Queried all songs longer than the global average track length to categorize "long-play" content.

3. Advanced Business Intelligence
Utilized complex SQL features like CTEs (Common Table Expressions) and Window Functions:

Artist Earnings: Calculated exactly how much each customer spent on the best-selling artist.

Genre Popularity by Country: Used ROW_NUMBER() and PARTITION BY to determine the most popular music genre for every country.

Top Spender per Country: Implemented Recursive CTEs and MAX() functions to find the highest-spending customer in each country, handling cases with tied spending amounts.

🛠️ Tools & Technologies
Language: SQL (PostgreSQL)

Database: Chinook Music Store Database

Concepts: Joins, Subqueries, Window Functions, CTEs, Recursive Queries, and Data Aggregation.

