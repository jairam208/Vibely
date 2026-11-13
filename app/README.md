# 🚀 Vibely - Full Stack CRUD Application

A full-stack web application built with **Spring Boot** and **React**, demonstrating standard Create, Read, Update, and Delete (CRUD) operations. Inspired by modern enterprise application patterns, this project integrates a robust Java backend with a dynamic React frontend interface.

---

## 🛠️ Tech Stack

* **Frontend:** React, React Router, HTML5, CSS3, JavaScript
* **Backend:** Java, Spring Boot, Spring Data JPA, H2 / Database
* **Build & Dependency Management:** Maven, Node.js / npm
* **Version Control:** Git & GitHub

---

## 📂 Project Structure

```text
vibely/
├── app/                  # React frontend application
├── src/                  # Spring Boot backend source code
├── pom.xml               # Maven configuration file for Java dependencies
└── README.md             # Project documentation
✨ Features
Full CRUD Operations: Create, view, update, and delete records seamlessly through an intuitive user interface.

RESTful API Architecture: Spring Boot backend exposes clean REST endpoints consumed by the React client.

Data Persistence: Uses Spring Data JPA for efficient database management and data operations.

Responsive UI: Clean, component-based layout built using React.

⚙️ Getting Started & Running Locally
To run this project locally on your machine, follow these steps:

Prerequisites
Java JDK (17 or higher recommended)

Node.js and npm

Maven

1. Clone the Repository
Bash
git clone https://github.com/jairam208/vibely.git
cd vibely

2. Run the Spring Boot Backend
Navigate to the backend directory and run the Spring Boot application using Maven:
Bash
mvn spring-boot:run
(The backend server will start locally, typically on port 8080).

3. Run the React Frontend
Open a separate terminal window, navigate to the app folder, install dependencies, and launch the development server:
Bash
cd app
npm install
npm start
(The React app will open locally, typically on port 3000).

💡 What I Learned
Building this project deepened my understanding of connecting a decoupled frontend framework (React) with a robust backend service (Spring Boot) via REST APIs, handling asynchronous state updates, and structuring full-stack application workflows.
