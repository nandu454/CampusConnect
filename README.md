# CampusConnect

A beginner-friendly campus event and club discovery website built with Java 17, Spring Boot, Thymeleaf, HTML, CSS, JavaScript and MySQL.

## Requirements
- Java JDK 17
- Maven 3.8+ (or newer)
- MySQL Server 8+

## Setup
1. Install Java 17, Maven and MySQL.
2. In MySQL, create a database named `campusconnect` (or let the app create it if your MySQL user has permission).
3. Open `src/main/resources/application.properties` and replace `YOUR_MYSQL_PASSWORD` with your local MySQL root password. Do not share that password.
4. Open this project folder in VS Code.
5. Open Terminal > New Terminal and run: `mvn spring-boot:run`
6. Open `http://localhost:8080`.

Pages:
- `/` Home and event registration
- `/bookings` Look up bookings by email
- `/admin` Demo event management and registration list

The admin page is intentionally unprotected for classroom demonstration only. Do not deploy publicly without authentication and security hardening.
