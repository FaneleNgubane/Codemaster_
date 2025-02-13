# Codemaster_ 🚀

A **Spring Boot-powered coding quiz game** designed to test and improve programming skills! 💻✨

## 🔹 Features

✅ **OAuth2 Authentication** – Secure login with Google.
✅ **MongoDB Storage** – Store user data and quiz progress.
✅ **Multiple Question Types:**
   - 📚 **Multiple-Choice** – Select the correct answer.
   - 🔍 **Code Completion** – Fill in the missing code.
   - ⏳ **Timed Coding Challenges** – Solve coding tasks before time runs out.
✅ **JWT Authentication** – Secure API access.
✅ **Spring Boot & REST API** – Scalable backend architecture.

## 🔹 Tech Stack

🛠 **Technologies Used:**
- Java 17
- Spring Boot 3.4.2
- MongoDB
- Spring Security
- OAuth2
- JWT
- Lombok
- Maven

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed:
- [Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Maven](https://maven.apache.org/download.cgi)
- [MongoDB](https://www.mongodb.com/try/download/community)

### Installation

1. **Clone the Repository**
   ```sh
   git clone https://github.com/FaneleNgubane/Codemaster_.git
   cd Codemaster_
   ```

2. **Configure Environment Variables**
   - Set up OAuth credentials (Google OAuth2)
   - Configure MongoDB connection
   - Define JWT secret in `application.properties` or `.env`

3. **Build and Run**
   ```sh
   mvn clean install
   mvn spring-boot:run
   ```

## 📌 API Endpoints

| Method | Endpoint          | Description              |
|--------|------------------|--------------------------|
| POST   | `/auth/login`    | User authentication      |
| GET    | `/quiz/questions` | Fetch quiz questions     |
| POST   | `/quiz/submit`    | Submit quiz answers      |


## 📬 Contact

📧 **Fanele Ngubane**  
GitHub: [FaneleNgubane](https://github.com/FaneleNgubane)

