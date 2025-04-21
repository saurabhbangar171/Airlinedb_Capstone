# Airlinedb_Project:
This project is a comprehensive capstone assignment built on a relational airline booking database, designed to strengthen SQL querying skills using real-world, normalized data structures. The project emulates a real airline's backend system and challenges the learner to solve insightful data problems across bookings, flights, aircrafts, and passenger logistics.

# Project Overview:
The AirlineDB schema simulates a realistic airline management system where:
Bookings may include one or more tickets.

Tickets represent individual passengers (assumed unique) and may include one or more flight segments (i.e., connecting or return flights).

Flights are defined between two airports but vary by departure date.

Boarding Passes are issued only if the flight is part of a passenger’s ticket.

Aircrafts define seating configurations and classes (Economy, Comfort, Business).

Airports are linked to time zones and flight operations.

This schema is ideal for practicing complex SQL queries like joins, aggregations, window functions, conditional filters, and formatting.


# Data Schema Highlights: 

bookings: Booking reference, booking date, and total amount

tickets: Ticket number, passenger ID, and name

ticket_flights: Each flight segment associated with a ticket

flights: Scheduled and actual departure/arrival data, aircraft used, status

boarding_passes: Seat assignment for checked-in passengers

seats: Seat configuration for each aircraft by fare class

aircrafts: Model and range of aircrafts

airports: Metadata including timezone and location

![image](https://github.com/user-attachments/assets/ae28ae8a-5458-41b5-b4fd-8c66f244cf9e)


# Objective:
To answer a set of real-world business questions using SQL that test your ability to:

Extract and transform flight data

Identify passenger booking behaviors

Detect anomalies like delays or cancellations

Aggregate and format time-sensitive data

Use advanced SQL clauses such as RANK(), ROW_NUMBER(), and WITH clauses (CTEs)

# Tools & Platform
SQL Playground: Skillovilla SQL Playground

SQL Engine: PostgreSQL (or compatible)

Editor: Queries submitted via Word document interface


# Deep understanding of relational databases in the aviation domain.

# Strong SQL query writing and optimization skills.

# Hands-on experience with real-world business data analysis scenarios.

# Practice with date/time functions, joins, aggregations, and subqueries.

