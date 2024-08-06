# Chinook Project

This project focuses on the Chinook database, a sample database commonly used for learning and practicing SQL and database management.

## Overview

The Chinook database is a sample database that models a digital media store, including tables for artist, album, track, customer, employee, and more. It is designed to help users learn SQL and perform database management tasks.

## Files

1. **sql_Chinook_queries**

   - **Description:** Contains various SQL queries used to interact with the Chinook database. These queries cover a range of operations, including data retrieval, manipulation, and complex joins to demonstrate SQL capabilities.

2. **PowerBI_Chinook**

   - **Description:** Includes Power BI files that utilize data from the Chinook database to create visualizations and reports. These files illustrate how to transform SQL data into actionable insights and interactive dashboards.

3. **Analysis_Chinook_Database**
   - **Description:** Provides a comprehensive analysis of the Chinook database schema. This file includes detailed information on table relationships, data types, and the overall database structure.

## Database Schema

The Chinook database consists of the following key tables:

1. **Artist**

   - **Description:** Contains information about artists.
   - **Key Fields:** ArtistId, Name

2. **Album**

   - **Description:** Contains information about albums released by artists.
   - **Key Fields:** AlbumId, Title, ArtistId (foreign key referencing Artists)

3. **Track**

   - **Description:** Contains information about individual tracks within albums.
   - **Key Fields:** TrackId, Name, AlbumId (foreign key referencing Albums), GenreId (foreign key referencing Genres)

4. **Genre**

   - **Description:** Contains information about music genres.
   - **Key Fields:** GenreId, Name

5. **Customer**

   - **Description:** Contains information about customers who have made purchases.
   - **Key Fields:** CustomerId, FirstName, LastName, Email, Country

6. **Invoice**

   - **Description:** Contains invoice details for customer purchases.
   - **Key Fields:** InvoiceId, CustomerId (foreign key referencing Customers), InvoiceDate, Total

7. **InvoiceItem**

   - **Description:** Contains details of individual items within each invoice.
   - **Key Fields:** InvoiceItemId, InvoiceId (foreign key referencing Invoices), TrackId (foreign key referencing Tracks), Quantity, UnitPrice

8. **Employee**
   - **Description:** Contains information about employees working at the store.

## Getting Started

To start working with the Chinook database:

1. **Run SQL Queries:** Use the `sql_Chinook_queries` file to practice SQL commands and perform database operations.
2. **Explore Reports:** Open the Power BI files in `PowerBI_Chinook` to see how data from the Chinook database is used to create interactive reports and dashboards.
3. **Understand the Schema:** Review `Analysis_Chinook_Database` to get a clear picture of how the database is structured and how its tables are interconnected.

## How to Use

- **SQL Queries:** Load the queries into your preferred SQL tool or database client to execute and experiment with them.
- **Power BI:** Use Power BI Desktop to view and interact with the provided Power BI files.
- **Schema Analysis:** Use the analysis file to get detailed insights into the database design and table relationships.

## Contributions

We welcome contributions to this project:

- **Report Issues:** If you find any bugs or have suggestions, please report them in the Issues section.
- **Pull Requests:** Feel free to submit pull requests with improvements or new features.

## Contact Information

If you have any questions or need further assistance, reach out to [mobinamozayan@gmail.com]. Happy learning!
