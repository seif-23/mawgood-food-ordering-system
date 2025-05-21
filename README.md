# Mawgood-Food-Ordering-System
## Overview
This project is a complete Oracle Forms & Reports application designed for managing a simple restaurant ordering system with role-based access.

## Features

### 1. Login Screen

* Users enter username and password.
* The system validates user credentials and user type (admin or cashier).
* Based on the user role, it redirects to the appropriate interface.


### 2. Admin Interface

* **Manage Users:**

  * Full CRUD operations on users (Create, Read, Update, Delete).
  * Navigation buttons to move through records: First, Last, Next, Previous.
* **Manage Menu:**

  * Perform CRUD operations on menu items.
* **Manage Reports:**

  * Placeholder for reports management (work in progress).

### 3. Cashier Interface

* Create and manage orders.
* Add order items with quantities to each order.


## Database Components

* **Users Table:** Stores users with their roles (`admin` or `cashier`).
* **Menu Table:** Stores menu items and their prices.
* **Orders Table:** Tracks each order, linked to the user who placed it.
* **OrderItems Table:** Contains the details of items per order.

## Triggers and Sequences

* **Order ID Sequence and Trigger:** Automatically generates incremental order IDs.
* **Order Total Trigger:** Updates the total order amount after insert, update, or delete on order items.

#How to Run
mmust install oracle db(recomended 11g2 release 11.2),web logic(recomended 10.3.6),forms and reports(recomended 11.1.2.0) remcomended install on virtual windows using vm ware(windows 7)
first create the data base with codes at data base code folder at the repo and connect with the same user u made the db in to oracle forms and reports
then run weblogic as adminstrator then run oracle forms and reports as adminstrator
and put all .fm files in the same folder at windows , cahnge the path at pl/sql code at trigers and run each screen alone then run from login and congrats u have the program
## Team Members

* Seif Magdy
* Ahmed Madah
* Mahmoud Metwaly
* Mohamed Tamer

## Notes

* The project uses Oracle Forms and Reports for the front-end UI and PL/SQL triggers and procedures for backend logic.
* The reports management module is currently under development.


