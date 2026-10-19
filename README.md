# Online Shopping Management System

## 1. Project Overview

The Online Shopping Management System is a UML modelling project that represents the structure of an online shopping platform.

The system is designed to manage customers, products, shopping carts, orders, and payment records.

The main objective of this project is to demonstrate how UML class diagrams can be used to model the structure and relationships of a software system.

## 2. Project Objectives

* Identify the main classes of an online shopping system.
* Define class attributes and methods.
* Model relationships between classes using UML.
* Represent associations, compositions, and multiplicities.
* Understand the structure of a software system before implementation.

## 3. System Classes

The project contains seven main classes:

1. **Customer** — manages customer information.
2. **Product** — stores product information and availability.
3. **ShoppingCart** — manages products selected for purchase.
4. **CartItem** — represents a product entry in a shopping cart.
5. **Order** — represents a customer's purchase.
6. **OrderItem** — represents a product entry in an order.
7. **Payment** — manages payment records.

## 4. UML Relationships

The class diagram represents the following relationships:

* Customer — ShoppingCart: Association.
* Customer — Order: Association.
* ShoppingCart — CartItem: Composition.
* CartItem — Product: Association.
* Order — OrderItem: Composition.
* OrderItem — Product: Association.
* Order — Payment: Association.

The diagram also specifies multiplicities to indicate how many objects can participate in each relationship.

## 5. Project Scope

### Included Features

* Customer registration and profile management.
* Product information and stock management.
* Shopping cart management.
* Order creation and tracking.
* Payment record management.

### Excluded Features

* Physical delivery management.
* Supplier and warehouse management.
* Advanced financial reporting.
* Implementation of a complete website or mobile application.

## 6. Repository Contents

* `README.md` — project documentation.
* `Online_Shopping_UML.pdf` — exported UML class diagram.
* `Online_Shopping_Report.pdf` — project report in PDF format.

## 7. Tools Used

* **diagrams.net (draw.io)** — for creating the UML class diagram.
* **GitHub** — for version control and project submission.

## 8. Author

**Name:** Jesse Binja 
**RollNumber:** 202512173
**Project:** Online Shopping Management System
**Assignment:** UML Class Diagram Modelling
