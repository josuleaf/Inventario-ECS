# **Inventory Management System**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
This repository contains the source code for the project:

Web-Based Inventory Management System for ECS Electrotelecom – Automated Administration of Technological Resources
J. Castro

This project was developed as part of the Final Graduation Project at Universidad Estatal a Distancia (UNED), Costa Rica.

---

## Project Overview
This project consists of a full-stack web-based Inventory Management System designed and implemented for a real telecommunications company in Costa Rica.
The system is built to automate stock control processes in a real production environment, transforming manual operational workflows into a structured and secure digital service.
> The solution reduced inventory management time by approximately 70%, significantly improving operational efficiency.

### Core features

- User management (registration, login, roles)
- Inventory item registration and tracking
- Stock updates and movement history
- Automated low-stock alerts via email (Nodemailer)
- Dashboard for monitoring inventory status
- Search and filtering capabilities
- Secure REST API endpoints

## System Architecture

The application follows a RESTful client-server architecture with clear separation of concerns between frontend and backend.

### Frontend Layer
The Frontend layer code is located inside the [Front-end folder](frontend) it focuses on:
- User-friendly and intuitive graphical interface
- Responsive design using Bootstrap
- Secure communication with backend via REST APIs
- Role-based interface rendering

### Backend Layer
The Backend Layer code is located inside the [Back-end folder](backend). It's built with Node.js and Express.js and it focuses on:
- RESTful API design
- JWT-based authentication and authorization
- Role-Based Access Control (RBAC)
- Middleware-based architecture for modularity
- Encryption of sensitive data
- Integration with external email services for automated notifications

## Security features
Security was a key focus during development. The system includes:

- JWT Authentication for secure session management
- Role-Based Access Control for permission enforcement
- Password hashing using bcrypt
- Sensitive data encryption
- CORS configuration for secure cross-origin communication
- Secure environment variable management

