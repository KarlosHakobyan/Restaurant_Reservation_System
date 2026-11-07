# 🏠 Smart Home Management System

A Full-Stack Smart Home Management System designed to manage homes, rooms, and connected smart devices through a centralized application.

The project demonstrates a modular application architecture with a separate backend and frontend, providing a foundation for managing smart home environments.

## 📌 Project Overview

The Smart Home Management System allows users to organize their smart home infrastructure by managing homes, rooms, and devices.

The application is divided into two independent modules:

- **Backend:** RESTful API responsible for business logic, data management, and database communication.
- **Frontend:** User interface for interacting with the smart home management system.

## 🏗️ Project Architecture

```text
Smart_Home_Project/
│
├── smart-home-backend/
│   └── Backend application
│
├── smart_home_frontend/
│   └── Frontend application
│
└── README.md
```

### Backend

The backend is responsible for:

- Application business logic.
- REST API endpoints.
- Database communication.
- Entity management.
- Repository and service layers.
- CRUD operations.

### Frontend

The frontend provides the user-facing application and communicates with the backend through API requests.

Its purpose is to provide an interface for managing smart home resources.

## 🛠️ Technologies

### Backend
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Microsoft SQL Server
- RESTful API

### Database
- Microsoft SQL Server
- Relational database design
- Entity relationships

### Frontend
- Separate frontend application (`smart_home_frontend`).

## ⚙️ Core Concepts

The project is organized around the following entities:

- **Home** – Represents a smart home.
- **Room** – Represents an individual room within a home.
- **Device** – Represents a smart device assigned to a room.

These entities form the foundation for organizing and managing smart home resources.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/KarlosHakobyan/Smart_Home_Project.git
```

```bash
cd Smart_Home_Project
```

### 2. Backend Setup

Navigate to the backend directory:

```bash
cd smart-home-backend
```

Configure your database connection in the application's configuration file.

Example configuration:

```properties
spring.datasource.url=jdbc:sqlserver://localhost:1433;databaseName=SmartHomeDB;encrypt=true;trustServerCertificate=true
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

Make sure Microsoft SQL Server is running and the database connection settings match your environment.

Run the application using your IDE or Maven:

```bash
./mvnw spring-boot:run
```

On Windows:

```bash
mvnw.cmd spring-boot:run
```

### 3. Frontend Setup

Navigate to the frontend directory:

```bash
cd smart_home_frontend
```

Install dependencies and start the development server using the package manager configured by the frontend project.

## 📂 Repository Modules

| Directory | Description |
|---|---|
| `smart-home-backend` | Backend application and API |
| `smart_home_frontend` | Frontend application |
| `.idea` | IDE project configuration |

## 🎯 Project Goals

- Practice Full-Stack application development.
- Implement RESTful API architecture.
- Work with Spring Boot and JPA.
- Design relational database structures.
- Implement CRUD operations.
- Separate application responsibilities into independent modules.
- Build a foundation for smart home automation.

## 🔮 Future Improvements

- User authentication and authorization.
- Real-time device status monitoring.
- Smart device control and automation.
- Device categories and configurations.
- Notifications and event management.
- Dashboard with device statistics.
- Improved responsive user interface.

## 👨‍💻 Author

**Karlos Hakobyan**

GitHub: [@KarlosHakobyan](https://github.com/KarlosHakobyan)

---

⭐ If you find this project interesting, feel free to explore the repository and follow its development.
