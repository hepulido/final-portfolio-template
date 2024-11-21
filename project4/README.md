Project #4: Inventory App - Deployment Focus
GitHub Repository: https://github.com/Team-Blue-Multiverse/Inventory

High-Level Overview
* Purpose:
    * A web-based platform for managing inventory.
    * Allows users to view, add, update, and delete products in the inventory system.
    * Ensures efficiency and accuracy in stock management.

* Target Users:
    * Inventory managers and business owners.
    * Users who need to:
        * Track stock levels.
        * Manage product information.
        * Ensure smooth inventory operations.

* Job Formation:
    * Maintains accurate inventory records.
    * Automates stock updates.
    * Provides real-time product availability.

* Inspiration:
    * Addresses challenges of manual inventory management:
        * Inaccuracies.
        * Inefficiencies.
    * Goal: Create a seamless, user-friendly web app for businesses.

Important Features

* Inventory Management:
    * Add, update, delete, and view product details.
* Product Information:
    * Displays product names, descriptions, quantities, and prices.
* User-Friendly Interface:
    * Simple and intuitive design.
* API Integration:
    * RESTful API for programmatic interaction with the system.

STAR Interview Breakdown

Situation:
* Businesses needed a reliable digital solution for efficient inventory management.
* A strong deployment strategy was crucial to ensure scalability and reliability.

Task
* Designed and deployed an inventory app using:
    * React for the front-end.
    * Express.js for the back-end API.
    * SQLite for the database.
* Focused on smooth configuration, deployment, and access for users.

Action
* Configured:
    * React front-end and Express back-end for seamless integration.
    * Node.js scripts for managing builds.
* Deployed the app manually to a cloud hosting service.

Result
* Enabled stable and accessible app deployment for users.
* Minimal downtime and reliable operations.
* Provided an organized, real-time inventory management tool.

Technologies Used

Front-end:
* React (v18.2.0).
* React Router (v6.21.1).
* Tailwind CSS (v3.3.5).
Back-end:
* Express (v4.17.1) for RESTful API.
* SQLite3 (v5.1.1) for the database.
* Sequelize (v6.23.2) for ORM.
Dependencies:
* CORS (v2.8.5) for cross-origin requests.
* dotenv (v16.0.0) for environment variables.
* Nodemon (v2.0.19) for server restarts during development.
* Parcel (v2.8.3) for bundling the front-end.
Testing:
* Jest (v27.1.0) for unit testing.
* Supertest (v6.3.3) for API testing.
* React Testing Library (v14.0.0) for React components.

Competencies

1. Deployment Management:
    * Situation: Needed a reliable deployment process to manage front-end and back-end integration.
    * Actions:
        * Configured React and Express builds.
        * Deployed manually to a cloud service.
    * Results:
        * Enabled minimal downtime.
        * Ensured smooth application availability.

2. Containerization & Application Management:
    * Situation: Ensured reliable deployment without containerization tools.
    * Actions:
        * Set up consistent build scripts for front-end and back-end.
        * Ensured seamless communication between client and server.
    * Results:
        * App ran smoothly across environments.
        * Gained deeper deployment knowledge without using containerization.