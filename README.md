# Bill Splitter Application

## Overview

The Bill Splitter application is a web-based platform that helps users manage shared expenses efficiently. It allows users to create teams, add expenses, split costs among members, and track payments. The application ensures that only the team creator has the authority to settle expenses, while other members can request payment confirmation.

## Features

- **User Authentication**: Secure login and registration.
- **Team Management**: Create and manage teams.
- **Expense Tracking**: Add, edit, and delete shared expenses.
- **Split Expenses**: Divide costs fairly among team members.
- **Payment Requests**: Members can request payment confirmation.
- **Payment Settlement**: Only the team creator can mark expenses as settled.
- **Database Management**: Uses MySQL for data storage.
- **API Documentation**: Integrated Swagger for API testing and exploration.

## Tech Stack

### Backend:

- **Spring Boot** (Java)
- **MySQL** (Database)
- **Spring Security** (Authentication & Authorization)
- **JWT** (Token-based authentication)
- **Swagger OpenAPI** (API Documentation)

### Frontend:

- **React.js** (User Interface)
- **Tailwind CSS** (Styling)

### Other Tools & Libraries:

- **Lombok** (Code simplification)
- **CSRF Protection** (Security)
- **RESTful API** (Backend communication)

## Database Schema

The database consists of the following tables:

- **users**: Stores user details.
- **teams**: Stores team information.
- **team_members**: Manages team memberships.
- **expenses**: Stores expense details.
- **expense_splits**: Records individual shares in an expense.

## API Documentation

Swagger UI is available for testing API endpoints:

- **Swagger UI**: [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)
- **OpenAPI Docs**: [http://localhost:8080/v3/api-docs](http://localhost:8080/v3/api-docs)

## Links

| Component | Repository Link |
| --------- | --------------- |
| **Frontend** | [BillSplitter-Frontend](https://github.com/amit8683/BillSplitter-Frontend) |
| **Backend**  | [BillSplitter-Backend](https://github.com/amit8683/BillSplitter_Back-End) |

## Security & Authorization

- **JWT-based authentication**: Ensures secure access.
- **Role-based access control**: Only the team creator can settle expenses.
- **CSRF Protection**: Prevents cross-site request forgery.

## Additional Resources

- [Project Documentation (PDF)](https://github.com/amit8683/Bill_Splitter/blob/main/Er.pdf)
- [Presentation (PPT)](https://github.com/amit8683/Bill_Splitter/blob/main/Bill_Splitter_Presentation_Updated.pptx)

## Contributors

- **Your Name** - Amit
