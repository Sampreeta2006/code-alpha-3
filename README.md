Name:v.sampreeta
Company:code alpha
Id:CA/N1/5703
Domain:java programming
Duration:15.11.2024-15.12.2024
Task 3:hotel reservation system
Overview:
The HotelReservationSystem is a Java program that simulates the functionality of a hotel booking system, allowing customers to search for available rooms, make reservations, and view booking details. The program manages hotel rooms, reservations, and the payment process in a simplified manner. Here's a breakdown of how it works:

Main Components:
Room Class:

Represents individual hotel rooms.
Each room has attributes like roomNumber, category (e.g., Single, Double, Suite), isAvailable (availability status), and price.
The class includes methods for retrieving room details and changing availability.
Reservation Class:

Stores reservation details such as the room being reserved, the customer's name, the check-in and check-out dates, and the payment status.
The class includes methods to access these details and update payment status.
Hotel Class:

Manages a collection of rooms and reservations.
It provides functionalities to:
Initialize predefined rooms.
Search for available rooms by category.
Make a reservation for a specific room.
Process payments (simulated as always successful).
View reservation details.
Main Method (HotelReservationSystem):

This is the user interface, where the program displays a menu for the user to interact with.
The user can:
Search for Rooms: Find available rooms by category (e.g., Single, Double, Suite).
Make a Reservation: Select a room, enter personal details, and specify check-in and check-out dates to make a booking.
View Reservation Details: Check the reservation details by entering the room number.
Exit: Exit the program.
