
# MongoDB Data Analysis with PyMongo and Jupyter Notebook


This project involves setting up a Jupyter Notebook environment, performing database operations using PyMongo, and conducting exploratory data analysis on a MongoDB database. The tasks are divided into three parts.



## Acknowledgements

UNC Chapel Hill Bootcamp Datasource

## TASK BREAKDOWN ##
## Part 1: Database and Jupyter Notebook Set Up ##

Setting up the Environment
Create a Jupyter Notebook file with the extension .ipynb.


Import the necessary libraries, including PyMongo for database interaction and Pretty Print (pprint) for displaying data.

Create a connection to the MongoDB server using the Mongo Client.

Database and Collection Verification
List the databases available in MongoDB and verify that the uk_food database is present.

List the collections within the uk_food database and ensure that establishments is one of them.

Use the find_one() method and Pretty Print to display one document from the establishments collection as a sample.

## Part 2: Update the Database ##
Data Insertion and Manipulation
Insert the supplied data for "Penang Flavours" into the establishments collection.

Perform a query to find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.

Update the "Penang Flavours" document with the correct value for BusinessTypeID.

Perform a query to delete all documents in the collection where "Dover Local Authority" is the value for LocalAuthorityName.

Use the count_documents() method to check the number of documents before and after the removal of the Dover documents.

Use the update_many() method to convert the latitude and longitude fields from strings to decimal numbers and the RatingValue to integers.

## Part 3: Exploratory Analysis ##
Data Analysis and Visualization
For Question 1, perform a query to find establishments with a hygiene score of 20. Use count_documents() to verify the count and display the first few results in a Pandas DataFrame.

For Question 2, perform a query to find establishments in London with a RatingValue greater than or equal to 4 using the $regex operator. Use count_documents() to verify the count and display the first few results in a Pandas DataFrame.

For Question 3, perform a query to find the top 5 establishments with a RatingValue of 5, sorted by the lowest hygiene score, nearest to "Penang Flavours." Use the sort() and limit() methods in PyMongo. Display the results in a Pandas DataFrame.

For Question 4, build an aggregation pipeline to count the number of establishments with a hygiene score of 0 in each Local Authority area. Sort the results in descending order and print the top ten local authority areas. Display the results in a Pandas DataFrame.
 

### Conclusion ###
This project showcased the power of data management, analysis, and visualization using Python, Jupyter Notebook, and MongoDB. It underscored the importance of data integrity, cleanliness, and accuracy in drawing meaningful insights. Furthermore, the project demonstrated how well-structured queries and data manipulation can yield valuable findings for decision-makers and researchers alike.

## Authors

- [Ashlin Shinu George](https://github.com/)

