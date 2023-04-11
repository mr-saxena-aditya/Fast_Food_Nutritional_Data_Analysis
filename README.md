"Fast Food Nutritional Data Analysis and Categorization using Python"

# Fast_Food_Nutritional_Data_Analysis

This Python program for a Junior Developer Assessment reads nutritional data from a CSV file, stores it in a database, categorizes food items, and generates a visualization of the results using a Python visualization library.

Problem Statement:
You are given a CSV file containing information about nutritional facts for fast food restaurants. Your task is to write a Python program to:
1. Read the CSV file and store the data in a database
1. The DB can be Relational, NoSQL or SQLite
2. Docker can be used as well just ensure that the migration scripts are in the Dockerfile, Image or in the code
2. Read the data from the database you set up NOT from the CSV
3. Calculate the average, minimum and maximum calories for each restaurant and rank the restaurants by those that have the least amount of carbs on average.
4. Show this data for the Top 5 restaurants as a chart using any Python visualization library
5. Categorize the type of food items as any ONE of the following based on the names of the food and/or the nutrition: Main, Side, Dessert
6. For items categorized as Main add a second sub-categorization this time where an item can have ONE OR MORE values of the following: Chicken, Beef, Seafood, Pork, Other
7. Export this information as a CSV file called food_cats.csv
