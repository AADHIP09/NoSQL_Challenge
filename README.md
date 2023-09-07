# NoSQL_Challenge

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. The purpose of this activity is to help the journalists and food critics at Eat, Safe, Love, a UK-based food magazine decide where to focus future articles. 
The Activity will consist of 3 parts: 

> Part 1: Database and Jupyter Notebook Set Up

> Part 2: Update the Database

> Part 3: Exploratory Analysis

## Part 1: Database and Jupyter Notebook Set Up: 

The following tasks were completed: 

1. Import the data provided in the establishments.json file from Terminal. Name the database uk_food and the collection establishments. 

2. Within the notebook, import the libraries you need: PyMongo and Pretty Print (pprint).

3. Create an instance of the Mongo Client.
   
4. List the databases you have in MongoDB. Confirm that uk_food is listed.

5. List the collection(s) in the database to ensure that establishments is there.

6. Find and display one document in the establishments collection using find_one and display with pprint.
   
7. Assign the establishments collection to a variable to prepare the collection for use.


## Part 2: Update the Database:

The following tasks were completed:

1. Adding a new restaurant to the database.

2. Find the 'BusinessTypeID' for "Restaurant/Cafe/Canteen" and return only the 'BusinessTypeID' and 'BusinessType fields'.

3. Update the new restaurant with the 'BusinessTypeID' found in the previous step.

4. Remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted

5. Use 'update_many' to convert latitude and longitude to decimal numbers

6. Use 'update_many' to convert RatingValue to integer numbers.


## Part 3: Exploratory Analysis:

The following tasks were completed:

1. Use 'count_documents' to display the number of documents contained in the result.

2. Display the first document in the results using pprint.

3. Convert the result to a Pandas DataFrame, print the number of rows in the DataFrame, and display the first 10 rows

The following questions were answered: 

1. Which establishments have a hygiene score equal to 20

2. Which establishments in London have a RatingValue greater than or equal to 4

3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"

4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas
