Car Rental  class_lab - Object-Oriented Programming (OOP) in Python

This lab implements a simple car rental system using object-oriented programming (OOP) concepts in Python. The system includes several classes that demonstrate inheritance, encapsulation, and polymorphism.
Classes Overview:

    Vehicle: A base class representing a vehicle with a color attribute and a method to retrieve the color.
    Car: A subclass of Vehicle that adds a boolean attribute for winter tires and overrides the toString() method to include tire information.
    Truck: A subclass of Vehicle that adds a boolean attribute for trailers and overrides the toString() method to include trailer information.
    Garage: A class that can park any Vehicle (Car or Truck) and provides a description of the parked vehicle.
    GarageTester: A class used to test the functionality of the Garage and Truck classes.
    Customer: A class representing a customer, with attributes for name and address.

Features:

    Demonstrates OOP principles like inheritance, method overriding, and class composition.
    Supports parking different types of vehicles (Car or Truck) in a Garage and printing their descriptions.
    Example usage is provided in the GarageTester.py file.

Running the Lab:

    Clone the repository.
    Ensure all the Python files are in the same directory.
    Run GarageTester.py to test the functionality.
