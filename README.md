# Sakila-DVD-Rental-database-analysis 
## This project is part of Programming for Data Science Nanodegree with Udacity 
Introduction
In this project, we have queried the Sakila DVD Rental database. Using SQL The Sakila Database holds information about a company that rents movie DVDs. For this project, we have queried the database to gain an understanding of the customer base, such as what the patterns in movie watching are across different customer groups, how they compare on payment earnings, and how the stores compare in their performance. For assistance in the queries

And here is the schema for the DVD Rental database is provided below.

![dvd-rental-erd-2](https://user-images.githubusercontent.com/54390114/213307245-e2a1bfe8-b99c-4908-b61d-be42775af56b.png)



actor — contains actors data including first name and last name.

film — contains films data such as title, release year, length, rating, etc.

film_actor — contains the relationships between films and actors.

category — contains film’s categories data.

film_category — containing the relationships between films and categories.

store — contains the store data including manager staff and address.

inventory — stores inventory data.

rental — stores rental data.

payment — stores customer’s payments.

staff — stores staff data.

customer — stores customer’s data.

address — stores address data for staff and customers

city — stores the city names.

country — stores the country names.

### Questions to work upon for analysis
#### Questuion 1:
understand more about the movies that families are watching. The following categories are considered family movies: Animation, Children, Classics, Comedy, Family and Music.
Create a query that lists each movie, the film category it is classified in, and the number of times it has been rented out.
    
#### Questuion 2:
provide a table with the family-friendly film category, each of the quartiles, and the corresponding count of movies within each combination of film category for each corresponding rental duration category.

#### Question 3:
find out how the two stores compare in their count of rental orders during every month for all the years we have data for. Write a query that returns the store ID for the store, the year and month and the number of rental orders each store has fulfilled for that month.

#### Question 4:
find out the top 10 customers per thier total paid amount 
