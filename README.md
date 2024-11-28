VRV Security - Authentication, Authorization, and Role-Based Access Control (RBAC) System


Introduction
This project is a Spring Boot application developed for VRV Security to demonstrate the implementation of Authentication, Authorization, and Role-Based Access Control (RBAC). The system ensures that users can register, log in, and log out securely, with access to resources managed based on user roles such as Admin, User, and Moderator.

Features
User Registration: Users can register by providing a username and password and role.
User Login: Registered users can log in to receive access tokens.
Role-Based Access Control (RBAC): Access to resources is controlled based on user roles. Different roles have specific permissions to access certain endpoints.
Secure Password Storage: User passwords are securely hashed using BCrypt.
Database Integration: User and role information is stored and managed using a relational database.
Technologies Used
Spring Boot: Framework for building the application.
Spring Security: Provides authentication and authorization.
Spring Data JPA: For database interactions.
Maven: Dependency management and build tool.
Prerequisites
Java 8 or higher
Maven
An IDE (e.g., IntelliJ IDEA, Eclipse)
