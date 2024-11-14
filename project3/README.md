Bank Project - Deployment Focus
High-Level Overview
Project Purpose: The Bank Project is a web application designed to simulate banking operations, allowing users to manage their accounts, view transactions, and perform basic banking functions such as deposits and withdrawals.

Users
The primary users are individuals seeking a user-friendly platform to manage their banking activities, including checking balances, transferring funds, and viewing transaction history.

Job Formation
The application provides users with the ability to perform essential banking tasks efficiently, reducing the need for physical bank visits and streamlining financial management.

Inspiration
The inspiration behind the Bank Project came from the increasing demand for digital banking solutions and the desire to create a simple yet effective tool that mimics real banking functionalities for educational purposes.

Important Features
Account Management: Users can create, view, and manage their bank accounts.
Transaction History: A feature that allows users to view their transaction history.
Deposit and Withdrawal: Users can perform deposit and withdrawal transactions.
Fund Transfer: Enables users to transfer funds between accounts.

STAR 
Situation: The application was created to provide a practical solution for users to manage their banking needs digitally while simulating the functionalities of a real bank. A robust deployment strategy was essential to ensure accessibility and reliability.

Task: The deployment structure included Docker for containerization, GitHub Actions for continuous integration and deployment (CI/CD), and Render for hosting the application. The design process involved configuring Docker containers, setting up CI/CD pipelines, and ensuring smooth deployment.

Action: I created a Dockerfile to define the application environment, including the necessary dependencies and configurations. I set up GitHub Actions workflows to automate testing and deployment processes, ensuring that every code change was automatically built and deployed to Render.

Result: The final deployment setup enabled rapid iteration and ensured that the application was always up-to-date and stable. Screenshots can illustrate the CI/CD pipeline in GitHub Actions and the application running on Render.

Technologies
Containerization:

Docker for packaging the application and its dependencies into a portable container.
CI/CD:

GitHub Actions for automating the build and deployment process.
Deployment:

Render for hosting the application and managing the production environment.
Back-end:

Spring Boot (v3.2.7) for building the RESTful API.
Java (v17) for application development.
Database:

PostgreSQL for persistent data storage.
H2 Database for in-memory testing.
Dependencies:

Spring Boot Starter Data JPA for database access.
Spring Boot Starter Security for authentication and authorization.
Spring Boot Starter Web for building web applications.
JJWT for JWT handling.
Lombok for reducing boilerplate code in models.
Spring Boot Starter Test for testing.

Competencies
Deployment Management
Full Text: Implement and manage deployment processes for applications.

Situation: In the Bank Project, I was responsible for deploying the application in a way that ensured reliability and ease of updates.

Actions: I utilized Docker to containerize the application, ensuring consistency across development and production environments. I created a Dockerfile that included all dependencies, which streamlined the deployment process. Additionally, I set up GitHub Actions to automate the CI/CD pipeline, allowing for automatic testing and deployment with every push to the repository.

Results: The deployment strategy significantly improved the efficiency of releasing updates and ensured that the application was always in a deployable state. This experience enhanced my skills in deployment management and made the deployment process seamless.

Connection to Project: This competency is directly related to my role in the Bank Project, where I managed the deployment processes and implemented best practices for continuous integration and delivery.

Containerization
Full Text: Utilize containerization technologies to ensure application portability and consistency across environments.

Situation: For the Bank Project, I aimed to ensure that the application could run consistently in different environments without issues related to dependencies.

Actions: I created Docker images for the application, which encapsulated the code and its environment. I defined a Dockerfile that outlined the steps to build the image, including installing dependencies and configuring the application. This containerization approach allowed for easy replication of the application environment.

Results: The use of Docker made the deployment process more reliable, as it reduced the chances of discrepancies between development and production environments. This experience improved my understanding of containerization and its role in modern software development.

Connection to Project: This competency is closely linked to my work on the Bank Project, where containerization was a critical component of the deployment strategy.