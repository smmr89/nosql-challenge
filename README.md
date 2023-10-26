# nosql-challenge

This repository contains solutions to the NoSQL Challenge Module 12

## Part 1: NoSQL Setup

* This analysis can be found in the notebook: "NoSQL_setup.ipynb"
* This part was concerned with setup for the analysis
* Data was imported from the `establishments.json` file via the terminal using `mongoimport`
* A database called 'uk_food' with a collection called `establishments` was created
* A new restaurant was input into the collection, its insertion verified and 'BusinessTypeID' updated in line with other businesses in the database
* Restaurants located in Dover were dropped, and data types were corrected using `update_many`

## Part 2: NoSQL Analysis

* This analysis can be found in the notebook: "NoSQL_analysis.ipynb"
* An instance of the `MongoClient` is created, and the database and collection assigned to variables
* Exploratory data analysis is performed in line with the requirements of the challenge

## References

MongoDB Documentation - https://www.mongodb.com/docs/