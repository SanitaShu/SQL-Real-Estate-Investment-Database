# Real Estate Investment Database | SQL Server

## Project Overview

This project focuses on designing and implementing a relational database for a real estate investment group managing forestland, agricultural land and other properties in Latvia.

The database was developed to organise property information, track land ownership and support investment analysis and management reporting.

## Tools & Technologies

- Microsoft SQL Server
- SQL
- Relational Database Design
- Entity-Relationship Diagrams (ERD)
- Database Normalisation (1NF, 2NF, 3NF)

## Database Structure

The database consists of five interconnected tables:

- **Manager** – information about company managers
- **Company** – companies within the investment group
- **Property** – real estate assets and acquisition details
- **Land_unit** – individual land units belonging to properties
- **Land_type** – forestland, agricultural land and other land categories

Primary and foreign keys were implemented to establish relationships and maintain referential integrity.

## SQL Implementation

The project includes:

- Database and table creation
- Primary and foreign key constraints
- Data insertion and updates
- SQL queries using JOIN, GROUP BY, HAVING, CASE, SUM and COUNT
- Aggregated reporting and investment analysis

## Business Analysis

SQL queries were developed to answer practical business questions, including:

1. What properties does the investment group own?
2. How many hectares are owned by land category?
3. How many properties and hectares are managed by each manager?
4. Which land units are dominated by agricultural land?
5. Which properties are dominated by forestland?
6. How much has each company invested in property acquisitions?
7. Which are the ten most expensive acquisitions based on EUR per hectare?

## Key Learning Outcomes

- Designing relational databases based on business requirements
- Developing conceptual and logical data models
- Applying database normalisation
- Writing SQL queries for business reporting
- Analysing investment portfolios using aggregated data
- Translating business questions into database queries

## Project Documentation

The repository contains a PDF documenting the database design, SQL implementation, sample queries and results.

## Project Scope

This is a portfolio project demonstrating practical SQL, relational database design and analytical reporting skills.
