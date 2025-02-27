# Vending Machine - Java Project

## Overview
This Java-based **Vending Machine** project simulates a vending machine system where users can browse, select, and purchase items. The project includes administrative features for managing inventory, pricing, and transactions.

## Features
- User authentication system for admin and customers.
- Display available products with prices.
- Purchasing mechanism with payment processing.
- Inventory management (add, update, delete items).
- Data persistence using CSV file handling.

## Installation & Setup
### Prerequisites
- **Java JDK 8 or later**
- **Eclipse IDE (optional, for development)**
- **Git (optional, for version control)**

### Steps to Run
1. **Clone or Download the Repository**
   ```sh
   git clone https://github.com/your-repository/vending-machine-java.git
   ```
2. **Navigate to the Project Directory**
   ```sh
   cd vending-machine-java
   ```
3. **Compile the Java Files**
   ```sh
   javac -d bin src/javaProject/*.java
   ```
4. **Run the Application**
   ```sh
   java -cp bin javaProject.Main
   ```

## Project Structure
```
|-- src/
|   |-- javaProject/
|       |-- Admin.java
|       |-- BiddingClass.java
|       |-- CsvFileWriter.java
|       |-- Input.java
|       |-- Item.java
|       |-- LoginField.java
|-- bin/ (compiled .class files)
|-- data/ (CSV files for storing inventory and transactions)
|-- README.md
|-- .project (Eclipse project settings)
```

## Usage
- **Admin Login:** Manage inventory and view reports.
- **User Interface:** Browse and purchase items from the vending machine.
- **Payment Handling:** Simulated through virtual currency input.


