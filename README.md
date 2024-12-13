# World Database Exploration Project (MySQL)

## Overview

This project involves exploring the **World Database** using **MySQL** queries. The project includes analysis and data exploration of global statistics, such as countries, continents, cities, and their respective attributes. The goal is to run complex SQL queries to uncover insights into the world's population, geography, and other demographics.

## Project Structure

- **world.sql**: The main database schema and data file. This file contains the creation of the `country`, `city`, and related tables with initial data.
- **queries.sql**: A collection of SQL queries used to explore and analyze the world data in various ways.
- **README.md**: Documentation for understanding and using the project.

## Tables in the Database

### 1. **country**
- Contains information about each country in the world.
  - **Columns**: `Code`, `Name`, `Continent`, `Region`, `SurfaceArea`, `Population`, `LifeExpectancy`, `GNP`, etc.
  
### 2. **city**
- Contains data on cities located in different countries.
  - **Columns**: `ID`, `Name`, `CountryCode`, `District`, `Population`, etc.

### 3. **continent** (if included)
- Contains data about continents, used to group countries.
  - **Columns**: `ContinentID`, `ContinentName`.

## Setup Instructions

### 1. Install MySQL

You need MySQL installed on your machine to work with the database. If you don't have MySQL installed, follow the steps below:

- **MySQL Installation Guide**: [MySQL Install](https://dev.mysql.com/doc/refman/8.0/en/installing.html)

### 2. Example Queries
1- This query will return information from the city table.
![MySql 1](https://github.com/user-attachments/assets/28f53eb6-f1bb-4e8b-a1e9-d8157ac7f3a7)


2- This query will return country information
![MySQL 2](https://github.com/user-attachments/assets/14d54320-5431-4ed9-b610-6786be10fc16)

3- This query will return numbers of cieties in the USA
![MySql 3](https://github.com/user-attachments/assets/21786827-05e7-44c1-867e-5a73edbd8a6e)

4- This query will return the cities from Europian countries
![My Sql 4](https://github.com/user-attachments/assets/c5c6f7dd-b7e0-425f-a128-860a10278c43)







