Project #4: Inventory App - Deployment Focus
https://github.com/Team-Blue-Multiverse/Inventory/tree/main

High-Level Overview
Project Purpose
The Inventory App is a web-based platform designed to manage inventory for businesses or organizations. The app allows users to view, add, update, and delete products in an inventory system. It provides a simple and intuitive interface for managing inventory, ensuring efficiency and accuracy in stock management.

Users
The primary users are inventory managers and business owners who need to track stock levels, manage product information, and ensure smooth operations of inventory management.

Job Formation
The app helps users maintain accurate records of their inventory, automate stock updates, and provide real-time information on product availability. It serves as a tool to streamline the inventory management process, saving time and minimizing human error.

Inspiration
The inspiration behind the Inventory App came from the challenges businesses face in managing inventory manually, often leading to inaccuracies and inefficiencies. The goal was to create an easy-to-use web application that can integrate seamlessly with existing business operations.

Important Features
Inventory Management: Add, update, delete, and view product details.
Product Information: Displays product names, descriptions, quantities, and prices.
User-Friendly Interface: Simple UI to manage inventory easily.
API Endpoints: RESTful API for interacting with the inventory system programmatically.
STAR Interview Questions
Situation
The application was developed to provide a digital solution for businesses to manage their inventory in an efficient and organized manner. A strong deployment strategy was essential to ensure scalability and reliability in production.

Task
The deployment structure included using React for the front-end, Express.js for the back-end API, and SQLite for the database. The design process involved configuring the environment, setting up deployment tools, and ensuring smooth deployment of the app for easy access by users.

Action
I configured the deployment process by setting up the React front-end and Express back-end, ensuring the two worked seamlessly together. I used basic Node.js scripts to manage the front-end and back-end builds and set up manual deployment to a cloud hosting service.

Result
The final deployment setup allowed for easy manual deployment, ensuring that the app was accessible and stable for users. Screenshots can show the app running in the deployed environment and the server configurations.

Technologies
Front-end
React (v18.2.0) for building the user interface.
React Router (v6.21.1) for routing.
Tailwind CSS (v3.3.5) for styling.
Back-end
Express (v4.17.1) for building the RESTful API.
SQLite3 (v5.1.1) for the database.
Sequelize (v6.23.2) for ORM (Object Relational Mapping) with SQLite.
Dependencies
CORS (v2.8.5) for handling cross-origin requests.
dotenv (v16.0.0) for environment variable management.
Nodemon (v2.0.19) for automatic server restart during development.
Parcel (v2.8.3) for bundling the front-end application.
Testing
Jest (v27.1.0) for unit testing.
Supertest (v6.3.3) for API testing.
React Testing Library (v14.0.0) for testing React components.
Competencies
Deployment Management
Full Text: Implement and manage deployment processes for applications.

Situation
The Inventory App was developed to streamline inventory management, but to ensure that it could be reliably updated and maintained in production, a strong deployment process was needed.

Actions
I set up the front-end and back-end for deployment by configuring the React build scripts and ensuring they worked together with the Express API. I used Node.js scripts to manage the build and launch processes. The application was deployed manually to a cloud service to ensure that users had easy access to it.

Results
The deployment strategy allowed for easy management and manual updates. The application was available for users with minimal downtime. This project helped me develop a better understanding of deployment processes in full-stack applications.

Connection to Project
This competency relates to my role in the Inventory App, where I focused on configuring and managing the deployment process for the front-end and back-end applications.

Containerization and Application Management
Full Text: Utilize containerization technologies to ensure application portability and consistency across environments.

Situation
While containerization wasn’t used in this project, ensuring a reliable and consistent deployment process was still crucial for the successful launch of the Inventory App.

Actions
I ensured that the React front-end and Express back-end communicated seamlessly by setting up the server and client configurations. The build was performed using manual scripts that handled front-end and back-end deployment. This process ensured the app was accessible and running smoothly across all environments.

Results
The deployment process enabled the app to be deployed and run smoothly across various environments. This experience improved my understanding of deployment without relying on containerization.

Connection to Project
This competency is connected to my work on the Inventory App, where I configured the deployment process to ensure consistent behavior across development and production environments.