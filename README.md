# 🏦 Banking Application - CRUD Operations

A robust backend service for a Banking Application built with **Spring Boot**, **Spring Data JPA**, and **MySQL**. This project demonstrates full CRUD (Create, Read, Update, Delete) functionality for managing bank accounts, including core banking operations like deposits and withdrawals.

---

## 🚀 Features

- **Account Management**: Create, view, and delete accounts.
- **Banking Operations**: 
    - 💰 **Deposit**: Add funds to a specific account.
    - 💸 **Withdraw**: Securely deduct funds from an account.
- **RESTful API**: Standardized JSON-based communication.
- **Data Persistence**: Integrated with MySQL database for reliable storage.

---

## 🛠️ Technologies Used

- **Framework**: Spring Boot 3.2.5
- **Database**: MySQL
- **ORM**: Spring Data JPA (Hibernate)
- **Language**: Java 17
- **Build Tool**: Maven
- **Utilities**: Lombok (for cleaner code)

---

## 📂 Project Structure

```text
src/main/java/net/javaguides/banking/app/
├── controller   # REST API Endpoints
├── dto          # Data Transfer Objects
├── entity       # Database Models
├── mapper       # Entity-DTO Mapping
├── repository   # Database Access (JPA)
└── service      # Business Logic
```

---

## 📡 API Endpoints

### 💳 Account Endpoints
| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `POST` | `/api/accounts` | Create a new account |
| `GET` | `/api/accounts/{id}` | Get account details by ID |
| `GET` | `/api/accounts` | Fetch all registered accounts |
| `DELETE` | `/api/accounts/{id}` | Permanently delete an account |

### 💰 Transaction Endpoints
| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `PUT` | `/api/accounts/{id}/deposit` | Deposit funds into an account |
| `PUT` | `/api/accounts/{id}/withdraw` | Withdraw funds from an account |

---



## 📝 Author
- **GitHub**: [@Divyamsingh05](https://github.com/Divyamsingh05)

