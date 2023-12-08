# Project Overview
# Income, Budget and Expenses Tracker Application
## Overview
## Introduction
The Income, Expense, and Budget Tracker is a robust financial management application designed to help individuals or businesses efficiently manage their finances. This tool aims to provide users with a comprehensive platform to track income sources, monitor expenses, and create budgets for better financial planning and decision-making.

# Table of contents
- Features
- Technology used
- Prerequisites
- Installation Guide
- Installation Steps
- Usage and Configuration
- API Reference
- Troubleshooting
- Additional Notes

Key Features:
Income Tracking: Users can log various income sources such as salaries, investments, freelance work, etc., to have a clear overview of their earnings.

Expense Monitoring: The application allows users to categorize and record expenses, providing insights into where and how their money is being spent. Users can categorize expenses by type, date, and amount for better analysis.

Budget Management: With a budget creation feature, users can set financial goals, allocate funds to different categories, and monitor their spending against the set budgets. The system provides alerts and notifications when nearing or exceeding budget limits.

Customizable Reports: Generate detailed reports and visual representations of income, expenses, and budget performance over specific periods. This feature helps in analyzing spending patterns and identifying areas for potential savings.

Secure Authentication: Implement robust security measures such as user authentication, encryption of financial data, and secure login to ensure the safety of users' sensitive financial information.

This Income, Expense, and Budget Tracker is a Spring Boot-based RESTful API that enables users to manage their finances. It is a comprehensive financial management application designed to help users efficiently track their income, monitor expenses, and manage budgets. This tool provides a user-friendly interface to streamline financial tracking and aid in better decision-making regarding personal or business finances.



# Features
 1. Budget Management: Create, update, delete, and view budgets via RESTful endpoints.

 2. Warning Notifications: Receive warnings via API responses when nearing or exceeding budget limits.
 
 3. User-Friendly Interface: Offers an intuitive and easy-to-use interface for entering currencies and amounts to be converted.
 
 4. Date-based Warnings: Warnings provided based on approaching budget dates.
 
 5. Comparison: The application compares expenses against the set budget limits and provides warnings or notifications when a budget limit is 
    exceeded.

 6. Users can set and manage budgets for different spending categories.   

# Technology used

-  Java: Core programming language used for application logic.
-  Spring Boot: Framework used for creating the application and RESTful APIs.
-  Maven/Gradle: Dependency management and build automation tools.
-  RESTful APIs: For handling CRUD operations on income, expenses and budgets.

# Prerequisites
- JDK 11 or higher installed.
- Apache Maven for building the application.
- Your favorite REST API client (e.g. Talend, Postman) for testing API endpoints. 


# Installation Guide
- An operating system: Windows, macOS, or Linux.
- Java runtime enviroment(JRE): Install JRE version 8 or higher.
- Internet connection

# Installation Steps
## Getting Started
you will need:
  - Integrated Development Environment (IDE) such as IntelliJ IDEA or Eclipse
  - Maven or Gradle installed
## Step 1: Download or clone repository
### Download ZIP or Clone the Repository:
  - GitHub: Visit the repository page on GitHub (provide repository URL) and click on "Clone or download" > "Download ZIP."
  - Git: Alternatively, if you have Git installed, use git clone <repository URL> in your terminal or command prompt.

## Step 2: Set Up Environment
### Check Java Installation:
  - Open a terminal or command prompt and type java -version to confirm that Java is installed and properly configured.
  - Extract ZIP (If downloaded):
     - If you downloaded a ZIP file, extract it to a location of your choice.

## Step 3: Build and Run
### Build the Application (if necessary):
  - Depending on the project structure, you may need to build the application. 
  - Run the Application:
      - Execute the currency converter application using the provided executable file or command. For Java applications, you might run a command like java -jar <app-name>.jar
      - Add dependencies for:
         - springdoc-openapi-starter-webmvc-ui
         - spring-boot-starter-hateoas
         - spring-data-rest-hal-explorer
         - spring-boot-starter-actuator
         - spring-boot-starter-validation
         - jackson-databind
         - h2 in memory database

## Step 4: Usage and Configuration
### Usage:
   - Explore the user interface that provides Documentation(Spring doc open api application.
   - Configuration
      - The application requires configuration for dependencies.

   - Run the application.
   - Access the endpoints to perform CRUD operations on income, expenses and budgets.

## Use the provided API documentation for more details on endpoints.
   # API Endpoints
   - GET/users: Retrieve all users.
   - GET/users/{id}:retrieves user by id.
   - POST/users: Add a new user.
   - PUT/user/{id}: Update an existing user by ID.
   - DELETE/users/{id}: Delete a user by ID.
   - GET/income: Retrieve all income.
   - GET/income/{id}:retrieves income by id.
   - GET/income/{date}: retrieves income by date.
   - POST/income: Add a new income.
   - PUT/income/{id}: Update an existing income by ID.
   - DELETE/income/{id}: Delete an income by ID.
   - GET/budgets: Retrieve all budgets.
   - GET/budgets/{id}: Retrieves a budget by id.
   - GET/budgets/{date}: retrieves budget by date.
   - POST/budgets: Add a new budget.
   - PUT/budgets/{id}: Update an existing budget by ID.
   - DELETE/budgets/{id}: Delete a budget by ID.
   - PUT/budget/{category}: Update an existing budget by category.
   - GET/expenses: Retrieve all expenses.
   - GET/expenses/{id}: Retrieve an expenses by id.
   - GET/expenses/{date}: retrieves expenses by date.
   - POST/expenses: Add a new expenses.
   - PUT/expenses/{id}: Update an existing expenses by ID.
   - DELETE/expenses/{id}: Delete an expenses by ID.
   - PUT/expenses/{category}: Update an existing expenses by category.       
# Exceptions
  - Exceptions were customized and documented within the code in the case of an all exceptions.
  - It gives https status of HttpStatus.INTERNAL_SERVER_ERROR,HttpStatus.NOT_FOUND, and HttpStatus.BAD_REQUEST
## Step 5: Troubleshooting
   - Issues and Support: In case of any issues, refer to support forums for troubleshooting or guidance.
   - This code is still under production
     
## DOCUMENTATION REFERENCE
   - springdoc-openapi is used in this project to Automatically generate documentation.
    Check them out here:
> https://localhost:8080/swagger-ui.html
 It provides detailed information about all available endpoints, their usage, and request/response formats.

## Additional note
This project is still under production. 

