# software-eng-Assignment
Assignment 
GROUP ASSIGNMENT							

QUESTION ONE

Read carefully and understand the case study below to answer the two questions. Be as   innovative as possible.

 The railway reservation system functions as follows;
The passenger is required to fill in a reservation form giving detail of his journey. The counter clerk ensures whether the place is available. If so, entries are made in a register, tickets are prepared, amount is computed and cash is accepted. 
A booking statement is prepared in triplicate format from the reservation register. One copy is retained as office copy, the other is pasted to the compartment and third is passed on to the train conductor. Besides booking statement, cash statement is prepared at the end of each shift.

Prepare System Require Specification and system specification for above system problem.

Design a prototype for the case study

 System Requirements Specification (SRS) for Railway Reservation System:
1. Introduction: The Railway Reservation System is a critical component of the railway service, facilitating the booking and management of passenger reservations. The system aims to streamline the booking process, ensuring seat availability, generating tickets, and handling financial transactions efficiently.
2. Functional Requirements:
2.1 Reservation Form: Passengers should be able to fill in a reservation form, providing essential journey details such as destination, date, and class of travel.
2.2 Availability Check: The system should verify the availability of seats for the specified journey.
2.3 Reservation Record: Once availability is confirmed, the system should create a reservation record, including passenger information and journey details.
2.4 Ticket Generation: -The system should prepare tickets based on the reservation record, including passenger details, journey information, and a unique ticket identifier.
2.5 Amount Calculation: -The system should calculate the total fare for the reservation, considering the class of travel and any discounts or special conditions.
2.6 Payment Handling: -The system should accept cash from passengers as payment for their reservations.
2.7 Booking Statement: -A triplicate format booking statement should be generated, containing details of the reservation. Copies of the statement should be retained in the office, pasted in the train compartment, and provided to the train conductor.
2.8 Cash Statement: -At the end of each shift, a cash statement should be prepared, summarizing the total revenue collected during that shift.
3. Non-Functional Requirements:
3.1 Performance: -The system should be capable of handling a high volume of reservations and financial transactions efficiently.
3.2 Reliability: -The system must be reliable, ensuring that reservations are accurately recorded and tickets are generated without errors.
3.3 Security: -Secure payment handling and passenger data protection are essential. Access to sensitive data should be restricted to authorized personnel.
3.4 User Interface: -The user interface should be user-friendly, making it easy for passengers and clerks to navigate the system.
3.5 Scalability: -The system should be able to scale to accommodate an increasing number of passengers and reservations.

System Specification for Railway Reservation System: -The Railway Reservation System will be developed as a web-based application, providing a user-friendly interface for passengers and clerks. The system will use a secure database to store passenger information, reservation records, and financial transaction data.
Here is an overview of the system's architecture:
1. User Roles:
i.	Passenger
ii.	Counter Clerk
iii.	Train Conductor
iv.	Administrator
2. Modules:
2.1 Passenger Module:
i.	Users can create and manage their profiles.
ii.	Reserve seats for their journeys.
iii.	Make payments for reservations.
iv.	View and print their tickets.
2.2 Counter Clerk Module:
i.	Access to reservation form for booking on behalf of passengers.
ii.	Seat availability check.
iii.	Generate tickets and collect payments.
iv.	Prepare booking and cash statements.
2.3 Train Conductor Module:
i.	Access to booking statements for onboard verification.
ii.	Ability to validate passenger tickets during the journey.
2.4 Administrator Module:
i.	Manage user accounts and roles.
ii.	Monitor system performance.
iii.	Perform system maintenance and updates.
3. Technologies:
i.	Programming Language: Java or Python
ii.	Web Framework: Django or Spring Boot
iii.	Database: PostgreSQL or MySQL
iv.	Security: SSL for secure data transmission
4. Security Measures:
i.	User authentication and authorization.
ii.	Encryption for sensitive data.
iii.	Regular data backup and disaster recovery plan.
5. Prototyping:
To design a prototype for the Railway Reservation System, you can use a wireframe or mockup tool such as Balsamiq or Adobe XD. The prototype should visually represent the user interface, including screens for passenger registration, reservation form, availability check, ticket generation, and payment processing. Additionally, you can design screens for counter clerks, train conductors, and administrators to showcase the respective functionalities. Make sure to include placeholders for essential data and labels. The prototype should demonstrate the flow of the system, from passenger registration to booking statement generation.
Please note that a full-fledged system development would require the involvement of software developers, database administrators, and quality assurance professionals. The prototype serves as a visual guide to understand the system's user interface and functionality.



