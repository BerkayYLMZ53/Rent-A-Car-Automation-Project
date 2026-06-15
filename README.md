# 🚗 Car Rental Automation with C# OOP

This project is a **Car Rental System** desktop application developed in C# using Object-Oriented Programming (OOP) principles and a layered architecture. The system models data flows and entity structures common in vehicle leasing scenarios.

## 🎯 Project Objective and Key Features
Designed to digitize the daily operations of a car rental company, this automation system includes the following modules:
* **Customer Management:** Customer registration, information updates, driver's license validation, and active/inactive status tracking.
* **Fleet Management:** Registering vehicles with attributes such as brand, model, license plate, fuel type, transmission type, mileage, and daily rental rate.
* **Rental Workflows:** Associating customers with vehicles, calculating rental duration, tracking pickup/return dates, and generating total cost invoices.
* **Status Tracking:** Automatically updating a vehicle's status to "Rented" (Inactive) when leased, and reverting it to "Available" (Active) upon return.

## 💎 Applied Object-Oriented Programming (OOP) Principles

The project is structured around standard OOP concepts:
1. **Classes & Objects:** Real-world entities such as `Customer`, `Vehicle`, `Rental`, and `Invoice` are modeled as classes and managed through dynamic objects.
2. **Encapsulation:** Critical data such as license plates, customer national ID numbers, and financial figures are protected using `get` and `set` properties to control access and modifications.
3. **Inheritance:** Shared attributes among vehicle types (e.g., `PassengerCar`, `CommercialVehicle`) are inherited from a common base class (`Vehicle`) to reduce code redundancy.
4. **Polymorphism:** Methods for calculating rental rates or formatting system reports are defined as `virtual` and customized using `override` keywords to support flexible implementations.

## 🛠️ Technologies Used
* **Programming Language:** C# (.NET Framework / .NET Core)
* **User Interface Technology:** Windows Forms Application (WinForms)
* **Data Management:** SQL
```
