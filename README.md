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

## Part 3: Exploratory Analysis

