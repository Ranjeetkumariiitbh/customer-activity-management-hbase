# Customer Activity Management using HBase

## Project Overview

This mini project demonstrates customer activity management using Apache HBase, a distributed NoSQL database built on Hadoop.

The project covers table creation, inserting customer data, retrieving records, updating values, deleting specific columns, filtering records, counting rows, and managing table state.

## Technology Used

- Apache HBase
- Hadoop
- HBase Shell
- NoSQL
- Windows PowerShell

## Table Structure

Table Name: customer_activity

### Column Families

- profile
  - name
  - city
  - last_login

- ctivity
  - type
  - product
  - timestamp

## Operations Performed

1. Created the customer_activity table.
2. Inserted customer records using put.
3. Displayed all records using scan.
4. Retrieved complete rows using get.
5. Retrieved specific columns using get.
6. Filtered records using SingleColumnValueFilter.
7. Updated an existing value using put.
8. Deleted a specific column using delete.
9. Counted rows using count.
10. Checked table structure using describe.
11. Disabled and enabled the HBase table.

## Sample Customer Data

| Customer ID | Name | City | Product | Activity |
|---|---|---|---|---|
| C101 | Amit | Ahmedabad | Laptop | Purchase |
| C102 | Rahul | Delhi | Mobile | View |
| C103 | Priya | Mumbai | Headphones | Purchase |
| C104 | Neha | Bangalore | Tablet | Cart |
| C105 | Rohit | Pune | Laptop | Purchase |

## Result

The customer_activity table was successfully created and tested with HBase shell operations.

Final row count: **5**

## Learning Outcome

This project provided hands-on experience with Apache HBase, including its row-key based data model, column families, CRUD operations, filtering, scanning, and table administration.
