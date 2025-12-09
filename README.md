## carDealershipRDBMS

# Overview
This is part of a group project was developed as part of a university SQLite unit and focuses on designing and implementing a relational database system for a car dealership / vehicle hire business. Whilst given a scenario of a real-world business and how it would function, the use of database normalisation, referential integrity, constraints, and triggers accurately reflects the criteria of the scenario and models how a RDBMS would be applied in the real world. The schema supports personal and company clients, vehicle bookings and hires, depots, pricing tariffs, insurance, invoicing, and operational constraints

# Key Features of the Schema
The schema includes various features including:
 - Fully normalised relational schema
 - Extensive use of primary keys (including composite keys)
 - Foreign key constraints with appropriate CASCADE, SET NULL, and NO ACTION rules
 - Triggers to enforce business rules beyond basic SQL constraints
 - Clear modelling of many-to-many relationships via junction tables

# Constraints enforced in the Schema
The database enforces several real-world constraints, including:
 - A personal client can have a maximum of 2 phone numbers
 - A company can have a maximum of 2 phone numbers
 - A client can nominate up to 3 additional drivers
 - A depot can have up to 4 phone numbers
 - Vehicles must belong to a valid make and model
 - Insurance is optional when hiring a vehicle
 - Vehicles can be picked up and returned to different depots

By using constraints and SQL triggers, we are able to enforce all these rules and ensure the schema is fully functional with no issues. A copy of the case-study for this schema is attached in this repository.

# ERD Diagram for this schema
As part of the project, I have also developed an Entity-Relationship Diagram based of my schema, which is also attached in this repository

# Learning Outcomes
This project has allowed me to grasp an idea of how Relational Database Modelling Systems work in the real-world, and the processes involved in making them. This project involved extensive planning and refining in order to ensure that the schema is fully functional, while taking into all the possible edges cases that can ber encountered when testing the RDBMS. Furthermore, the project has helped me develop my SQLite3 skills and expose me to new functions, contraints and triggers to helped me translate "real-world" requirements into a robust SQL schema, while maintaining data integrity


