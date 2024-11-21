
# Hotel Management System

## Overview
The Hotel Reservation System is a Java-based console application that utilizes JDBC to connect to a MySQL database. It allows hotel staff to manage reservations by providing functionalities like reserving rooms, viewing reservations, retrieving room details, updating reservations, and deleting reservations.

## Features
#### 1. Reserve a Room
Allows users to book a room by entering the guest's name, room number, and contact number.

#### 2. View Reservations
Displays a list of all current reservations in a tabular format.

#### 3. Get Room Number
Fetches the room number for a given reservation ID and guest name.

#### 4. Update Reservations
Enables users to update guest name, room number, or contact number for an existing reservation.

#### - Steps to Update a Reservation
1. Choose Update Option
From the main menu, enter 4 to select "Update Reservations."

2. Enter Reservation ID
Input the ID of the reservation you wish to modify. If the ID doesn't exist, an error message is displayed.

3. Select Detail to Update
Choose what to update from the following options:

   - Guest Name 
   - Room Number
   - Contact Number
   - Return to Main Menu
4. Provide New Value
Enter the updated value for the selected detail. The system confirms the update or reports if it failed.

5. Repeat or Exit
After updating, you can modify another detail or return to the main menu.

#### 5. Delete Reservations
Allows the deletion of a reservation based on the reservation ID.

#### 6. Exit
Gracefully exits the system with a countdown.

### Prerequisites
- Java Development Kit (JDK) 
- MySQL Server version 
- MySQL JDBC Driver (mysql-connector-java)
- Basic understanding of SQL and database management