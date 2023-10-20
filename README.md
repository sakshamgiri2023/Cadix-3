# Cadix-3
A Bus ticket management system has been made by the Cadix-3 Team:  
1) Pranita
2) Sejal
3) Saksham
4) Madhav
 Thank You So much!!
Bus Reservation and Ticketing System
Table of Contents
Description
Features
Getting Started
Usage
Contributing
License
Description
The "Bus Reservation and Ticketing System" is a simple console-based Java application designed to manage bus ticket reservations. It allows users to book bus tickets for various destinations, view transaction details, and make payments. This system can be used by bus operators to manage passenger reservations efficiently.

Features
User authentication: The system requires users to log in with a username and password. The default credentials are "admin" for both username and password.
Destination information: Users can view available destinations, including their names, fares, and the number of available seats.
Ticket booking: Users can book tickets by specifying their name, choosing a destination, specifying the number of passengers, and indicating how many of them qualify for discounts (e.g., students, PWD, or senior citizens).
Ticket transaction: The system calculates the total fare for the booked ticket, considering discounts if applicable. It also tracks the payment status of each passenger.
Viewing passenger details: Users can search for passengers by name and view their booking details, including fare, seat, payment status, and more.
Transaction history: The system keeps a record of passenger details, including their destination, fare, number of passengers, and payment status.
User-friendly menu: The system uses a text-based menu to guide users through the ticketing process, making it easy to navigate.
Getting Started
To run the "Bus Reservation and Ticketing System" on your local machine, follow these steps:

Prerequisites: You need to have the Java Development Kit (JDK) installed on your machine.

Clone the Repository: You can clone the repository using Git:

bash
Copy code
git clone https://github.com/yourusername/bus-ticketing-system.git
Compile the Code: Navigate to the project directory and compile the Java source code:

bash
Copy code
javac BusReservationAndTicketingSystem.java
Run the Application: Run the compiled application:

bash
Copy code
java BusReservationAndTicketingSystem
Usage
Log In:

Username: admin
Password: admin
Main Menu:

Choose from options 1 to 5.
Options:
[1] Destination: View available destinations and their details.
[2] Buy Ticket: Book a ticket for a passenger.
[3] Transaction: Process ticket transactions, view total fare, and make payments.
[4] View: Search for passengers by name and view their details.
[5] Exit: Exit the application.
Booking a Ticket:

Enter passenger's name.
Select the destination number (1 to 5).
Specify the number of passengers and the number of passengers with discounts (e.g., students, PWD, or senior citizens).
The system calculates the fare, taking into account the discount, and displays the passenger's details.
Viewing Passenger Details:

Search for a passenger by name to view their booking details, including fare, number of passengers, and payment status.
Making Payments:

After viewing passenger details, you can make payments and receive change.
Exiting the Application:

Choose [5] Exit to close the application.
Contributing
Contributions to this project are welcome. If you have ideas for improving or extending the functionality, please feel free to submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.




