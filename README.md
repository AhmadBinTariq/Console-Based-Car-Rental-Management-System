# Console-Based Car Rental Management System

## Overview

This project is a Console-Based Car Rental Management System implemented in C++. It showcases the use of structs, file handling, and pointers to create a dynamic memory management system for managing a car rental service. The system offers different functionalities for both admins and customers, providing a complete management tool for car rentals.

## Features

### Admin Features
- **Login & Password Management**: Secure admin login and the ability to change the password.
- **Customer Management**: Add and remove customer accounts, and update customer information.
- **Car Management**: Add and remove cars from the system.
- **View Reports**: Access detailed reports on customer rental history and car usage, including damage reports.
- **Data Storage**: All data is stored in separate folders with individual files for each car and customer.

### Customer Features
- **Login**: Secure login to access the customer's account.
- **View Available Cars**: Display a list of cars available for rent.
- **Rent a Car**: Rent a car on an hourly or daily basis.
- **Return a Car**: Return a rented car and generate the bill.
- **Rental Reports**: Generate and view a report of all rental activities, including billing details.

## Project Structure

- **Car Data Folder**: Contains a list of all available cars and separate files for each car, storing details such as availability, rental frequency, and damage history.
- **Customer Data Folder**: Contains a list of all customers and individual files for each customer, storing personal information and login credentials.
- **Customer Records Folder**: Stores records of each customer's rental activities, including dates of rental and return, as well as detailed billing information.

## Admin Dashboard

1) Change Password
2) View Current Registered Cars and Customers
3) Add and Remove Customers
4) Update Customer Data
5) Add and Remove Car
6) Check Reports Related to Customers and Cars
7) Quit

## Customer Dashboard

1) Rent a Car
2) Return a Rented Car
3) View Available Cars
4) Generate Rental Reports
5) Quit

## How to Run

1) Clone the repository from GitHub.
2) Open the project in your preferred C++ development environment.
3) Compile and run the program.
4) Follow the prompts on the console to navigate through the admin or customer functionalities.

## Contributions
- Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss potential changes.
