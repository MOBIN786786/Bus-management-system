# Bus management system
A complete web-based Bus Management System designed to manage bus routes, schedules,ticket bookings, passengers, and admin operations.
This project is built using Java (Servlets/JSP), JDBC, and MySQL, following MVC architecture for clean and maintainable code.
This Bus Management System provides an online platform for managing daily bus operations.
It enables admins to manage buses, routes, drivers, schedules, and bookings, while users can view schedules and book seats easily.

Features:
          
Admin Features: 
      >> Add, update, and delete buses
      >> Add and manage routes
      >> Manage drivers and staff
      >> Create and update bus schedules
      >> View all bookings
      >> Generate reports

User Features: 
 ->User registration & login
 ->View available buses and routes
 ->Search buses by source & destination
 ->Book seats online
 ->heck booking status
 ->Cancel booking

Project Structure:

/BusManagementSystem

│── /src
│   ├── controller        (Servlets)
│   ├── dao               (Database logic)
│   ├── model             (Java Beans)
│── /webapp
│   ├── /views            (JSP pages)
│   ├── /assets           (CSS, JS, Images)
│── database.sql
│── README.md


🚍 How Bus Management System Works:
1. User opens the web application

Can be an admin or a passenger.

2. User selects an action

Admin → manage buses, routes, schedules, bookings.

Passenger → search buses, book tickets, view/cancel bookings.

3. Request is sent to the server

Browser sends the request to Java Servlets.

4. Servlet receives and processes the request

Reads user input

Validates data

Decides what operation to perform

5. Servlet connects to the database (JDBC)

Inserts data (e.g., new bus)

Reads data (e.g., search buses)

Updates data (e.g., edit schedule)

Deletes data (e.g., remove booking)

6. Database stores all information

Buses

Routes

Schedules

Users

Bookings

Drivers

7. Servlet sends data to JSP

Servlet prepares the result and forwards it to JSP page.

8. JSP displays the output to the user

Available buses

Booking confirmation

Admin dashboard

Error messages (if any)

9. User sees the result

Data is shown on the screen

User can perform next action

10. System repeats the cycle for each operation

Search → Book → Cancel → Update → etc.
