# SQL_Music_Store_Analysis
***
Music Store Database Description
***
**Database Management System (DBMS):** 
PostgreSQL is used as the relational database management system (RDBMS) for storing and managing the music store data.

**Database Tool:**
PgAdmin4 serves as the graphical user interface (GUI) tool for interacting with the PostgreSQL database. It facilitates database management, query execution, and visualization.

**Schema:**
The Music Store Database schema organizes the data into structured tables, defining the relationships between entities within the online music store.


![MusicDatabaseSchema](https://github.com/Ganeshkarwa/SQL_Music_Store_Analysis/assets/140792447/87ca02f9-144b-4780-8643-a995a6ac87a1)

**Key Tables:**
invoice: Contains information about customer purchases, including total amounts and timestamps.
invoice_line: Stores details about each individual track purchased in an invoice.
track: Represents individual music tracks available in the store, with attributes such as name, genre, and album association.
genre: Describes music genres available in the store.
employee: Includes details about store employees, potentially including sales-related information.
customer: Contains information about customers, their details, and support representative associations.

Analysis Focus:
The project aims to help beginners learn SQL by analyzing the music store database to derive insights that can aid the store's understanding of its business growth.

Project Questions:
The analysis addresses fundamental business questions such as top-selling genres, employee sales performance, average purchase amounts per customer, and considerations regarding album versus individual track sales.


Query Examples:
Sample SQL queries have been provided in the project to guide beginners in formulating their own queries based on the dataset.
