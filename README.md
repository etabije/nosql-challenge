Module 12 Challenge: nosql-challenge

Requirements

Part 1: Database and Jupyter Notebook Set Up
Your Jupyter notebook setup file must include:

The mongoimport command for importing establishments.json, ensuring it drops any existing establishments collection.
The database named uk_food with a collection named establishments.
Imports for PyMongo and Pretty Print, along with creating a Mongo Client instance.
Lists of databases and collections in MongoDB, confirming the presence of uk_food and establishments.
Use of find_one() and pprint to display a document from the collection and assign it to a variable.
Part 2: Update the Database
Your Jupyter notebook must contain:

Insertion of the "Penang Flavours" restaurant data into the establishments collection.
A query to find the BusinessTypeID for "Restaurant/Cafe/Canteen" and updating the "Penang Flavours" document with this ID.
A query to delete documents with "Dover Local Authority" and a count check before and after the deletion.
An update_many() query to convert latitude, longitude, and RatingValue fields to the correct data types.
Part 3: Exploratory Analysis
Your Jupyter notebook must answer the following questions:

Hygiene Score of 20: Query for establishments with this score, count the documents, and display the results in a DataFrame.
Establishments in London with RatingValue >= 4: Find these establishments, using regex and display the results.
Top 5 Establishments with RatingValue of 5: Query for establishments near "Penang Flavours," sort by hygiene score, and display the results.
Establishments with Hygiene Score of 0: Use an aggregation pipeline to count and sort these establishments by Local Authority.
Deployment and Submission



