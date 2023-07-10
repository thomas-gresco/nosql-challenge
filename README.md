# nosql-challenge
# Eat Safe, Love

This repository contains code snippets for setting up and updating a MongoDB database named "uk_food" with a collection named "establishments" using Python and the `pymongo` library.

## Part 1: Database and Jupyter Notebook Set Up

Import the data provided in the `establishments.json` file from your Terminal. Name the database uk_food and the collection establishments.

Within this markdown cell, copy the line of text you used to import the data from your Terminal. This way, future analysts will be able to repeat your process.

## Part 2: Update the Database
An exciting new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked you to include it in your analysis. Add the following restaurant "Penang Flavours" to the database.

Create a dictionary for the new restaurant data and insert it into the collection.

Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.

Update the new restaurant with the BusinessTypeID you found.

The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.

Some of the number values are stored as strings when they should be stored as numbers. Use update_many to convert latitude and longitude to decimal numbers.

Use update_many to convert RatingValue to integer numbers.

These code snippets demonstrate how to set up and update a MongoDB database using Python and the pymongo library. Feel free to modify and adapt them according to your specific needs.

# Exploratory Analysis

This repository contains code snippets for performing exploratory analysis on the MongoDB database using Python and the `pymongo` library.

## Part 3: Exploratory Analysis

In this section, we will perform various queries and analyses on the database. For each question, we will use the following steps:

1. Use `count_documents` to display the number of documents in the result.
2. Display the first document in the results using `pprint`.
3. Convert the result to a Pandas DataFrame, print the number of rows in the DataFrame, and display the first 10 rows.

### 1. Establishments with a Hygiene Score of 20

To find the establishments with a hygiene score equal to 20, execute the provided code snippet.

### 2. Establishments in London with RatingValue >= 4

To find the establishments in London with a RatingValue greater than or equal to 4, execute the provided code snippet.

### 3. Top 5 Establishments with RatingValue = 5, Sorted by Lowest Hygiene Score

To find the top 5 establishments with a RatingValue of 5, sorted by the lowest hygiene score and nearest to the new restaurant "Penang Flavours," execute the provided code snippet.

### 4. Establishments in Each Local Authority area with a Hygiene Score of 0

To determine the number of establishments in each Local Authority area with a hygiene score of 0, execute the provided code snippet.




