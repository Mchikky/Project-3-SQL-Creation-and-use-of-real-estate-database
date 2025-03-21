# Project 3: SQL - Creation and use of query to retrieve data from real estate database

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
  1. 1NF- removes repeated groups from a table to gurantee atomicity,
  2. 2NF- Lessens redundancy by eliminating partial redundancies
  3. 3NF- Reduces data duplication by removing transitive dependancies
- Identify primary key, secondary key, remove duplicates, eliminate redundant data, isolate relationships using database normalization
- Categorize data into 3 excel spreadsheets: bien (property), sales (ventes), and commune (city)
- Link tables through primary key and secondary keys using HLOOKUP function in Excel
- Import the database into MySQL using reverse engineering
  
  ![Deng_Chikaodili_3_schema_052022](https://github.com/user-attachments/assets/fee47aea-f01b-45a2-a292-e92fdd3639df)

## Data analysis
1. Total number of appartments sold in the first quarter of 2020.
<img width="822" alt="1" src="https://github.com/user-attachments/assets/c681fc2a-630a-4450-8685-c6b5b68cc37a" />

2. Proportion of appartment sold by number of rooms
<img width="824" alt="2" src="https://github.com/user-attachments/assets/4880ce48-9cd1-40a3-93a0-a0b98abedb78" />

3. List of 10 departments where the price of square metre is the most expensive
<img width="846" alt="3" src="https://github.com/user-attachments/assets/28004d9b-bdac-4bf3-8b7e-267a4ba87490" />

4. Price of an average square metre of a house in Ile de France
<img width="822" alt="4" src="https://github.com/user-attachments/assets/680062f5-13f1-45d0-b798-0b3d026d5337" />

5. List of the 10 most expensive appartments, their departments and number of square metres
<img width="828" alt="5" src="https://github.com/user-attachments/assets/9b9960c3-9ef1-4e79-bb30-35cfe477b9e2" />

6. Rate of change in sales figures between first and second quarter in 2020
<img width="652" alt="6" src="https://github.com/user-attachments/assets/9928fb65-4e09-4135-a783-1c61dda639ee" />

7. List of cities where the number of sales increased at least 20% between first and second quarter of 2020
<img width="659" alt="7" src="https://github.com/user-attachments/assets/2b4bcb53-09f2-45e0-98b5-79652c95cf8a" />

8. Difference in price percentage of square metre between an appartment of 2 rooms and an appartment of 3 rooms
<img width="654" alt="8" src="https://github.com/user-attachments/assets/c4466f41-8c0c-4e7a-845f-74f4177bf21d" />

9. Average value of property for the 3 top cities in departments 6, 13, 33, 59 and 69.
<img width="646" alt="9" src="https://github.com/user-attachments/assets/5df0d6b0-c878-4d0d-a4d0-9dd8c94387c5" />

## Insights
1. Total number of appartment sold in the first quarter of 2020 is 30897
2. 2 room apartment is the highest sold
3. Price of a square metre is highest in department 75
4. Average price of square metre of a house in Ile de France is approximately 5231
5. The most expensive appartment is found in department 75
6. Rate of change in sales figure is approximately 3.7%
7. Average value of property is highest in Nice based on the departments 6, 13, 33, 59 and 69 selected.
   
## Recommendations
- The real estate company should invest more in the construction of 2 room apartments since they sell faster than other types.
- More advertisement is needed to boost sales figures in subsequent years.
- For better Return on Investment (ROI) on properties, there is need to check the prices of appartments and houses in other departments.
