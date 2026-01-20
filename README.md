# Car Calculation System (Java)

A comprehensive Java-based desktop application for car management, comparison, and loan calculation. This system is designed to streamline the process of viewing car details, managing inventory, and helping users make informed decisions about car purchases.

## Features

- **Car Management**: Add, update, and manage car details including images, pricing, and specifications.
- **Car Comparison**: Compare different car models side-by-side to see differences in performance and features.
- **Loan Calculator**: Calculate monthly installments based on car price, interest rates, and down payments.
- **User Dashboard**: Role-based access for Admins and Standard Users.
- **Test Drive Scheduling**: System for users to book test drives for their preferred models.
- **User Authentication**: Secure login and registration system with Bcrypt password hashing.

## Screenshots

![Home Dashboard](screenshots/screenshot1.png)
*Home Dashboard and Car Selection*

![Car Management](screenshots/screenshot2.png)
*Car Inventory Management for Admins*

![Car Comparison](screenshots/screenshot3.png)
*Side-by-side Car Comparison Tool*

![Loan Calculator](screenshots/screenshot4.png)
*Integrated Loan and Installment Calculator*

![User Management](screenshots/screenshot5.png)
*User Accounts and Profile Management*

## Project Structure

- `src/finalproject/`: Contains all Java source files and GUI forms.
- `src/Images/`: Image assets for car models and UI elements.
- `nbproject/`: NetBeans project configuration files.
- `screenshots/`: App preview screenshots.

## Requirements

- Java JDK 8 or higher
- NetBeans IDE (optional but recommended for GUI editing)
- MySQL Database (for persistent storage)

## Setup

1. Clone the repository.
2. Import the project into NetBeans.
3. Configure your MySQL database settings in `DBConnection.java`.
4. Run `HomeFrame.java` to start the application.
