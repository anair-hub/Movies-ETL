# Movies-ETL
Module 8

# Objective
 Task is to create an automated pipeline that takes in new data, applies transformations and loads into postgres tables. Module 9 code will be refactored to create a function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data. In addition ETL process will be applied by adding the data to   PostgreSQL database.

## Deliverable 1: Write an ETL Function to Read Three Data Files

   Deliverable involves reading from three data files and creating three separate DataFrames.

![deliverable1a](Resources/delievrable1a.PNG)

![deliverable1b](Resources/delievrable1b.PNG)

![deliverable1c](Resources/delievrable1c.PNG)

## Deliverable 2: Extract and Transform the Wikipedia Data
 
  Extraction and transformed Wikipedia data is merged with the kaggle metadata in this deliverable. Try-execpt block has been leveraged to catch errors while extracting the IMBb IDs using a regular expression string and dropping duplicates.

![deliverable2a](Resources/deliverable2a.PNG)

![deliverable2b](Resources/deliverable2b.PNG)

## Deliverable 3: Extract and Transform the Kaggle data

  Extraction and transformed kaggle metadata along with MovieLens rating data is then converted into separated DataFrames via this deliverable 3. In addition kaggle metadata DataFrame is merged with Wikipedia movies DataFrame to create movies_df DataFrame.Final  movies_with_ratings_df DataFrame is created by merging MovieLens rating data and movies_df DataFrames. 

![deliverable3a](Resources/deliverable3a.PNG)

![deliverable3b](Resources/deliverable3b.PNG)

![deliverable3c](Resources/deliverable3c.PNG)

## Deliverable 4: Create the Movie Database

 This module involves addition of data from movies_df and MovieLens rating csv to PostgreSQL tables movies and ratings.

![deliverable4a](Resources/deliverable4a.PNG)

![deliverable4b](Resources/deliverable4b.PNG)

![deliverable4c](Resources/deliverable4c.PNG)

![deliverable4d](Resources/deliverable4d.PNG)

![deliverable4e](Resources/deliverable4e.PNG)

![deliverable5a](Resources/deliverable.PN5aG)