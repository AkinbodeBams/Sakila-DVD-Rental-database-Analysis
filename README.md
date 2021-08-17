# Sakila-DVD-Rental-database-Analysis
My analysis on Udacity's Sakila dvd rental project using PostgreSQl
Introduction

In this project, we have queried the Sakila DVD Rental database. The Sakila Database holds information about a company that rents movie DVDs. For this project, we have queried the database to gain an understanding of the customer base, such as what the patterns in movie watching are across different customer groups, how they compare on payment earnings, and how the stores compare in their performance. For assistance in the queries, the schema for the DVD Rental database was used as given in the dvd-rental-erd-2.pdf.

Local Environment Setup

Follow the steps provided below to setup the local environment with PostgreSQL and database

Step 1. Downloading PostgreSQL

First, we will need to install PostgreSQL on your local machine. The instructions below provide detailed description of the steps we need to take.

Installing PostgreSQL for Windows:

http://www.postgresqltutorial.com/install-postgresql/

Installing PostgreSQL for Mac OS:

https://www.postgresql.org/download/macosx/

Note: We need to write down the database superuser (postgres) password as we will need it to create the Sakila database once we have installed the PostgreSQL server.

Step 2. Downloading Sakila database

Once PostgreSQL server is installed, we will need to download the Movie database from this page: PostgreSQL Sample Database

Scroll down and click on the orange "Download DVD Rental Sample Database" button.

This will download a zipped file, and you will need to extract the dvdrental.tar file.

Step 3. Loading database

The next step is to load the DVD Rental database into our PostgreSQL server on our machine. We recommend using the PgAdmin tool. We can find the instructions to do so on the following link: Load PostgreSQL Sample Database.

The instructions are down ⅓ on this page under the header “Load the DVD Rental database using pgAdmin tool” .

Now, we need to follow the instructions all the way through the header titled "Verify the loaded sample database."

Once we have followed the instructions through the end of "Verify the loaded sample database.", we have now loaded the dvdrental sample database into our local PostgreSQL database server.

Step 4. Connecting back to the PostgreSQL server:

Now, we will relaunch PgAdmin III and click on the PostgreSQL server within the Object browser and enter our superuser (postgres) password.

Step 5. Connecting to the DVD rental database:

Next, we will click on the plus sign next to Databases to access the DVD rental database.

Step 6. Choose the DVD Rental database

Choose the dvdrental database under Databases.

We are now linked to the DVD rental database.

Step 7. Running Queries on your dvdrental database

Now, we are ready to run some queries. For that, we need to click on the SQL icon with a magnifying glass

Questions to work upon for analysis

Question 1

we want to understand the percentage difference in the time it takes for customers to return films they've rented , make sure you categorise them

Question 2

we would like to know how many orders have been made based on all ratings , do this by grouping by the ratings column of film

Question 3

there is a column called special features , investigate the column and uniquely identify the type of features in the column , use this to categorise the customer taste in special features in movies.

Category
Rental length category
Count
Question 4

we would like to know howour orders are doing across the cities , list the top 5 cities 
