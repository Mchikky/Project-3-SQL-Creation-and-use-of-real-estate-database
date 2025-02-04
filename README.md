# Project 3: SQL - Creation and use of real estate database

## Objective:
Create a real estate database using MySQL and query the database to retrieve some information.

## Mission:
- Prepare a data dictionnary showing the codes, description, type and length of codes.
- Design a schema showing relationships, entities and cardinalities of the database.
- Query the database to answer some questions on the sales of houses and appartments.

## Data source
OpenClassrooms: 3 Excel documents

## Data preparation
- Normalize data observing the 3 normal forms
- 1NF - removes repeated groups from a table to gurantee atomicity,
- 2NF - Lessens redundancy by eliminating partial redundancies
- 3NF - Reduces data duplication by removing transitive dependancies
- Identify primary key, secondary key, remove duplicates, eliminate redundant data, isolate relationships using database normalization
- Categorize data into 3 excel spreadsheets: bien (property), sales (ventes), and commune (city)
- Link tables through primary key and secondary keys using HLOOKUP function in Excel
- Import the database into MySQL using reverse engineering

## Data analysis and insights
1. Total number of appartments sold in the first quarter of 2020.
2. Proportion of appartment sold by number of rooms
- List of 10 departments where the price of square metre is the most expensive
- Price of an average square metre of houses in Ile de France
- List of the 10 most expensive appartments, theor departments and number of square metres
- Rate of change in sales number between first and second quarter in 2020
- List of cities where the number of sales increased at least 20% between first and second quarter of 2020
- Difference in price percentage of square metre between an appartment of 2 rooms and an appartment of 3 rooms
- Average value of property for the 3 top cities in departments 6, 13, 59 and 69

## Recommendations
