# nosql-challenge

# Part 1: Database and Jupyter Notebook Set Up

## Setup Instructions
- Import Data
- Import the data provided in the establishments.json file from your Terminal. - Name the database uk_food and the collection establishments. Copy the text you used to import your data from your Terminal to a markdown cell in your notebook.

## Notebook Setup
- Within your notebook, import the necessary libraries: PyMongo and Pretty Print (pprint).

## Create Mongo Client
- Create an instance of the Mongo Client.

## Confirm Database and Data Loading

- List the databases to confirm that uk_food is listed.
- List the collection(s) in the database to ensure that establishments is there.
- Find and display one document in the establishments collection using find_one  and display with pprint.
- Assign the establishments collection to a variable for use.

# Part 2: Update the Database

## Modifications
- Add New Restaurant
- Add a new restaurant, "Penang Flavours", to the database with specified details.

## Find and Update BusinessTypeID

- Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
- Update the new restaurant with the correct BusinessTypeID.
- Remove Establishments in Dover

## Check how many documents contain the Dover Local Authority.
- Remove any establishments within the Dover Local Authority from the database.
- Check the number of documents to ensure they were deleted.
- Convert String Values to Numbers

- Convert latitude and longitude to decimal numbers.
- Convert RatingValue to integer numbers.

# Part 3: Exploratory Analysis
## Analysis Instructions
For each question:

- Use count_documents to display the number of documents contained in the result.
- Display the first document in the results using pprint.
- Convert the result to a Pandas DataFrame, print the number of rows in the DataFrame, and display the first 10 rows.

## 1. Which establishments have a hygiene score equal to 20?
- Number of establishments with a hygiene score of 20: 41

## 2. Which establishments in London have a RatingValue greater than or equal to 4?
- Number of establishments with 'London' in Local Authority Name and RatingValue >= 4: 33

## 3. What are the top 5 establishments with a RatingValue of 5, sorted by the lowest hygiene score, nearest to "Penang Flavours"?
- Volunteer
- Plumstead Manor Nursery
- Atlantic Fish Bar
- Iceland
- Howe and Co Fish and Chips - Van 17

## 4. How many establishments in each Local Authority area have a hygiene score of 0?
- Number of documents in the result: 55

## Code Source
1. Learning Assistant
2. GitHub location: [git@github.com:jeffjunohkim/python-api-challenge.git](https://github.com/jeffjunohkim/nosql-challenge.git)
