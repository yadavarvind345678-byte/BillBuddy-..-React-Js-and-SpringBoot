# BillBuddy - Expense Sharing Application

BillBuddy is a simple and efficient expense-sharing application designed to help users manage and split expenses among friends and groups. The application follows a three-tier architecture and is built using modern web technologies.

## 🚀 Features

* **User Authentication:** Secure login and signup process.
* **Group Management:** Create different groups (Roommates, Trips, Office) and add friends.
* **Expense Tracking:** Add expenses and track who paid for what.
* **Split Logic:** Facility to split expenses equally or through custom logic.
* **Settlement:** View clear breakdowns of who owes whom and the total amounts.
* **Dashboard:** A centralized overview of your total balance and pending settlements.

## 🛠️ Tech Stack

**Frontend:**
* React.js (Hooks, Context API for State Management)
* CSS / Bootstrap (For responsive design)
* Axios (For API integration)

**Backend:**
* Spring Boot (Java)
* Spring Data JPA
* RESTful APIs

**Database:**
* MySQL

## 🏗️ Architecture

BillBuddy is based on a standard **Three-Tier Architecture**:
1. **Presentation Layer:** React.js frontend providing the user interface.
2. **Application Layer:** Spring Boot backend handling business logic and API requests.
3. **Data Layer:** MySQL database for storing user and transaction data.

## 📋 Prerequisites

* Java 17 or higher
* Node.js and npm
* MySQL Server
* Maven

## 🔧 Installation & Setup

### 1. Backend Setup (Spring Boot)
* Update your MySQL credentials in the `src/main/resources/application.properties` file.
* Navigate to the project directory and run:
  ```bash
  mvn install
  mvn spring-boot:run
