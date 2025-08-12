# FinanceAdvisor

A simple Spring Boot application for tracking and managing investments.
It uses **Spring Boot**, **Spring Data JPA**, **MySQL**, and **Thymeleaf**.


## ⚙️ Requirements
- Java 17 or later
- Maven 3.8+
- MySQL 8+
- An IDE (IntelliJ IDEA / Eclipse / VS Code with Java extension)

## 📦 How to Set Up

1. **Clone this repository**
git clone https://github.com/Yaseen2112/FinanceAdvisor.git
cd FinanceAdvisor

2. **Database Setup**
- Create a MySQL database:
  ```
  CREATE DATABASE financedb;
  ```
- Update `src/main/resources/application.properties` with your MySQL username and password.

3. **Run the Application**
mvn spring-boot:run
Or build and run:
mvn clean install
java -jar target/FinanceAdvisor-0.0.1-SNAPSHOT.jar

4. **Access the App**
- Open your browser at `http://localhost:8080/`

## 📜 application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/financedb
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD
spring.jpa.hibernate.ddl-auto=update

## 💡 Features
- Store investment records in a MySQL database
- Simple home page with Thymeleaf
- MVC structure

## 🤝 Contributing
Feel free to fork the repo and submit pull requests.

## 📄 License
This project is licensed under the MIT License.
