# Car-Rental-System
# Documentation
                   Car Class:
This class represents a car in the rental system.
Its associate properties are: make, model, registrationNumber, and isRented.
The Car class provides methods to rent and return the car, as well as getter and setter methods to access the car's details.
The toString() method is overridden to provide a string representation of the car object.
The CarTest class provides unit tests to ensure the functionality of the Car class.

                 Customer Class:
This class represents a customer in the rental system.
Its associate properties are: name and driverLicenseNumber.
The Customer class provides getter methods to access the customer's details.
The toString() method is overridden to give a string representation of the customer object.
The CustomerTest class provides unit tests to ensure the functionality of the Customer class.

                 RentalAgency Class:
This class shows the rental agency that aids in managing the car rental system.
It consists of two lists namely: cars and customers, which store the cars and customers.
The RentalAgency class provides methods to add cars and customers, find a car by its registration number, rent and return cars, and display the list of cars and customers.
The rentCar() and returnCar() methods deal with the rental and return operations.
The displayCars() and displayCustomers() methods gives a way to print the list of cars and customers.
The RentalAgencyTest class provides unit tests to ensure the functioning of the RentalAgency class.

               Main Class:
This class shows Car Rental System usage by creating a RentalAgency instance, adding cars and customers, renting and returning cars, and displaying the updated state of the system.
The provided solution implements the basic functionality of a Car Rental System using OOP principles in Java. It includes the necessary classes, methods, and test cases to ensure the system's correct behavior. The Car, Customer, and RentalAgency classes work together to manage the rental operations, and the test cases validate the implementation.
