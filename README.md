![Spotify](https://github.com/user-attachments/assets/b2038492-c22f-42c6-a530-166939183a03)

# Spotify-SQL-Project

This project includes a series of SQL queries designed to extract unique information from a simulated Spotify database.

## Purpose

The Spotify SQL Project explores and understands the data of a typical music store using SQL queries. The queries seek to answer key questions about Spotify's operations, client behaviors, and sales, providing valuable insights that can help the company grow and enhance profitability.

## Data

The database contains various tables that store the data. According to the queries, some of the tables are: employee, invoice, customer, invoice_line, track, genre, artist, album.

## Analysis Approach:

The project is segmented into three tiers of complexity: Easy, Moderate, and Advanced.

  * Easy Level: Includes basic searches focused on direct data retrieval, such as identifying top customers or employees.
  * Moderate Level: Encompasses intermediate queries that dig deeper, using complex JOIN operations, GROUP BY clauses, and aggregate functions like SUM and COUNT to derive more nuanced insights.
  * Advanced Level: Showcases the power of advanced SQL techniques. It prominently uses Common Table Expressions (CTEs) and window functions like ROW_NUMBER to answer complex queries.

## SQL Constructs Used:

The project showcases a wide range of SQL constructs to address various querying needs:

  * Data Retrieval: SELECT, DISTINCT, and FROM.
  * Filtering: WHERE, IN, and LIMIT.
  * Aggregation: SUM, COUNT, AVG.
  * Sorting: ORDER BY.
  * Joining Tables: JOIN.
  * Grouping Data: GROUP BY.
  * Window Functions: ROW_NUMBER.
  * Subqueries and Derived Tables: WITH (for CTEs).

## Business Questions to Answer

****Easy Level Questions:****
1. Who is the senior most employee based on job title?
2. Which countries have the most Invoices?
3. What are top 3 values of total invoice?
4. Which city has the best customers? We would like to throw a promotional Music.
5. Who is the best customer? The customer who has spent the most money will be declared the best customer. Write a query that returns the person who has spent the most money.

****Moderate Level Questions:****

1. Write query to return the email, first name, last name, & Genre of all Rock Music listeners. Return your list ordered alphabetically by email starting with A.
2. Let's invite the artists who have written the most rock music in our dataset. Write a query that returns the Artist name and total track count of the top 10 rock bands.
3. Returnallthetracknamesthathaveasonglengthlongerthantheaveragesonglength. Return the Name and Milliseconds for each track. Order by the song length with the longest songs listed first.


****Advance Level Questions:****

1. Find how much amount spent by each customer on artists? Write a query to return customer name, artist name and total spent.
2. We want to find out the most popular music Genre for each country. We determine the most popular genre as the genre with the highest amount of purchases. Write a query that returns each country along with the top Genre. For countries where the maximum number of purchases is shared return all Genres.
3. Write a query that determines the customer that has spent the most on music for each country. Write a query that returns the country along with the top customer and how much they spent. For countries where the top amount spent is shared, provide all customers who spent this amount.
