# Supermarket Billing Application (Console-Based)

## Overview
This **Supermarket Billing Application** is a console-based program developed using **Core Java**. The application automates the billing process in a supermarket, providing features such as itemized billing, tax calculation, and discount handling. It is designed with Object-Oriented Programming (OOP) principles for modularity and reusability.

## Features
- **Itemized Billing**: Generates a detailed bill listing all purchased items with quantities and prices.
- **Tax Calculation**: Automatically computes applicable taxes for each item.
- **Discount Handling**: Includes options for applying discounts on individual items or the entire bill.
- **Total Calculation**: Calculates the total amount payable after applying taxes and discounts.
- **User-Friendly Interface**: Simple and intuitive text-based user interface.

## Technologies Used
- **Programming Language**: Core Java
- **Concepts Used**: OOP principles (Inheritance, Polymorphism, Encapsulation)
- **Data Structures**: ArrayList, HashMap

## Getting Started
### Prerequisites
- Java Development Kit (JDK) version 8 or later
- IDE or text editor for Java (e.g., IntelliJ IDEA, Eclipse, or VS Code)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/karimullashaikdev/Supermarket_Project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd supermarket-billing-app
   ```
3. Compile the Java files:
   ```bash
   javac src/*.java
   ```
4. Run the application:
   ```bash
   java src.Main
   ```

## Usage
1. Start the application.
2. Enter the items purchased, along with their quantities and prices.
3. Apply any discounts if applicable.
4. View the final bill with itemized details, tax amounts, and the total payable.

## Application Workflow
1. **Input Items**: The user inputs the details of purchased items.
2. **Process Bill**: The application calculates subtotals, taxes, and discounts.
3. **Generate Bill**: A detailed bill is displayed with all calculations.

## Sample Output
```
Welcome to Supermarket Billing System
-------------------------------------
Enter item name: Milk
Enter quantity: 2
Enter price per unit: 50
Add another item? (yes/no): yes
Enter item name: Bread
Enter quantity: 1
Enter price per unit: 40
Add another item? (yes/no): no

Applying 10% discount...
Generating bill...

Itemized Bill:
1. Milk  - Qty: 2, Price: 50, Subtotal: 100
2. Bread - Qty: 1, Price: 40, Subtotal: 40
Tax: 14
Discount: 10
Total Payable: 144

Thank you for shopping with us!
```

## Project Structure
```
src/
├── Main.java          # Entry point of the application
├── Item.java          # Represents an item in the supermarket
├── BillGenerator.java # Handles bill processing and calculations
├── Discount.java      # Contains discount calculation logic
├── TaxCalculator.java # Contains tax calculation logic
```

## Future Enhancements
- Integration with a database for item and sales records.
- Adding support for multiple payment methods.
- Enhancing the interface with a GUI.
- Exporting bills as PDF or Excel files.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any queries or suggestions, feel free to reach out:
- **Name**: Karimulla Shaik
- **Email**: shaikkarimulladev@gmail.com
- **GitHub**: https://github.com/karimullashaikdev
