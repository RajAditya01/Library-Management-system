# 📚 Library Management System

This **Library Management System** (LMS) is a web-based application designed to automate library functionalities including book management, user memberships, transaction handling, and fine payments. The system supports both **Admin** and **User** roles with different permissions for maintenance, reporting, and transactions.

---

## 📋 Table of Contents

1. [Features](#features)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Modules](#modules)
6. [Validations](#validations)
7. [Project Structure](#project-structure)
8. [Contributing](#contributing)
9. [License](#license)

---

## ✨ Features

- **Role-Based Access**:
  - **Admin**: Full access to maintenance, reports, and transaction modules.
  - **User**: Limited access to reports and transactions.
- **Book Management**: Add, update, search, issue, and return books with automated validation and fine calculations.
- **Membership Management**: Register, renew, or cancel memberships with pre-set durations.
- **Fine Handling**: Automate fine calculations and ensure fines are settled before returning books.
- **Form Validations**: Ensure required fields are filled, with specific behavior for checkboxes and radio buttons.
- **Navigation**: Quick navigation to a flow chart of the LMS available on all pages.

---

## 🔧 Requirements

- **Node.js** and **npm**
- **MongoDB** database instance or URI
- **Git** (for version control)

### Environment Variables

Create a `.env` file in the root directory with the following:
```plaintext
PORT=5000
MONGO_URI=your-mongo-database-uri
JWT_SECRET=your-jwt-secret
