Car Rental System
This is a simple Car Rental System implemented in Java, showcasing the principles of Object-Oriented Programming (OOP). The system allows users to rent and return cars, providing basic functionalities like calculating rental prices, checking car availability, and managing customer records.

Classes
1. Car
Represents a car available for rental.
Properties:
carId: Unique identifier for the car.
brand: Brand name of the car.
model: Model name of the car.
basePricePerDay: Base rental price per day.
isAvailable: Availability status of the car.
Methods:
calculatePrice(int rentalDays): Calculates the total rental price based on the number of rental days.
rent(): Marks the car as rented.
returnCar(): Marks the car as available for rent.
2. Customer
Represents a customer who can rent a car.
Properties:
customerId: Unique identifier for the customer.
name: Name of the customer.
3. Rental
Represents a rental transaction, associating a customer with a rented car.
Properties:
car: The rented car.
customer: The customer who rented the car.
days: Number of days for the rental.
4. CarRentalSystem
Manages the entire car rental system.
Properties:
cars: List of available cars.
customers: List of registered customers.
rentals: List of active rentals.
Methods:
addCar(Car car): Adds a car to the system.
addCustomer(Customer customer): Adds a customer to the system.
rentCar(Car car, Customer customer, int days): Rents a car to a customer.
returnCar(Car car): Returns a rented car.
menu(): Displays a user-friendly menu for interacting with the system.
5. Main
Contains the main method to instantiate the CarRentalSystem, add cars, and initiate the system's menu.
Usage
Create instances of Car, Customer, and CarRentalSystem.
Add cars and customers to the system.
Use the menu provided by CarRentalSystem to rent and return cars.
Feel free to explore and modify the code to enhance or customize the functionalities according to your requirements. Enjoy using the Car Rental System!
