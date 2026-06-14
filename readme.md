# Football Ticket Booking System (SQL Assignment)

## Overview
This project is a simplified Football Ticket Booking System database designed to practice ERD concepts, SQL queries, joins, filtering, and aggregate functions.

The database contains three main tables:
- Users
- Matches
- Bookings

---

## Database Schema

### Users Table
Stores information about football fans and system users.

- user_id (Primary Key)
- full_name
- email
- role
- phone_number

### Matches Table
Stores football match details.

- match_id (Primary Key)
- fixture
- tournament_category
- base_ticket_price
- match_status

### Bookings Table
Stores ticket booking information.

- booking_id (Primary Key)
- user_id (Foreign Key → Users)
- match_id (Foreign Key → Matches)
- seat_number
- payment_status
- total_cost

---

## SQL Concepts Used
This assignment covers:

- SELECT filtering (WHERE, LIKE, ILIKE)
- Handling NULL values (IS NULL, COALESCE)
- INNER JOIN
- LEFT JOIN / FULL OUTER JOIN
- Aggregate functions (AVG)
- Sorting and LIMIT/OFFSET

---

## Key Queries Implemented

1. Filter Champions League available matches  
2. Search users by name patterns  
3. Handle missing payment status using COALESCE  
4. Join bookings with users and matches  
5. Show all users including those without bookings  
6. Find bookings above average cost  
7. Get top expensive matches (with offset)

---
