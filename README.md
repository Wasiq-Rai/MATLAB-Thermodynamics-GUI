# Hotel Management System
The Hotel Management System is a Java application that allows users to book hotel rooms. It provides a simple command-line interface for users to select available rooms, make bookings, and save the booking details.
## Features
* Display a list of available rooms and their details.
* Allow users to book a room by providing the room ID.
* Prevent booking if the room is already booked.
* Save booking details to a CSV file.
* Load and save user data to a CSV file.
## Usage
1. Run the HotelManagement class to start the application.
2.   Enter the user's first name and last name.
3.   Choose a room to book by entering the room ID.
4.   Repeat step 3 to book additional rooms.
5.   Enter "n" when prompted to book another room to complete the booking process.
6.   The bookings will be saved to a file named bookings.csv.
## File Structure
The project consists of the following files:
* **HotelManagement.java**: The main class that runs the Hotel Management System.
* **Room.java**: An abstract class representing a room with common attributes and methods.
*  **StandardRoom.java and DeluxeRoom.java**: Concrete classes representing specific types of rooms.
*  **RoomDB.java**: A database class for managing the list of available rooms.
*  **Bookable.java and Cancellable.java**: Interfaces for bookable and cancellable items.
*  **User.java**: A class representing a user with first name, last name, and ID.
*  **UserManager.java**: A class for managing user data and saving it to a file.
*  **Booking.java**: A class representing a booking with user and room details.
