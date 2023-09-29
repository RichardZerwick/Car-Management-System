# Car-Management-System

## Overview
The Car Management System is a web application that allows users to manage clients and their associated cars. It provides a user-friendly interface for adding, updating, and deleting clients and their cars. This README provides information on the functionality of the application and instructions for setting up and running the app locally.

## Functionality
### Clients Page
View Clients: 
Users can view a list of clients, including their names and email addresses.
Add Client: Users can add a new client by clicking the "Add Client" button and providing the client's name and email address.
Update Client: Users can update an existing client's name and email address by clicking the "Update" button next to the client and providing the updated information.
Delete Client: Users can delete a client and all associated cars by clicking the "Delete" button next to the client. A confirmation dialog will appear to confirm the deletion.
Cars Page

View Cars: Users can view a list of cars associated with a selected client, including their make, model, year, and registration number.
Select Client: Users can select a client from the dropdown list to view and manage cars associated with that client.
Add Car: Users can add a new car for the selected client by clicking the "Add Car" button and providing the car's make, model, year, and registration number.
Update Car: Users can update an existing car's details (make, model, year, and registration number) by clicking the "Update" button next to the car and providing the updated information.
Delete Car: Users can delete a car by clicking the "Delete" button next to the car. A confirmation dialog will appear to confirm the deletion.

## Prerequisites
Before you begin, ensure you have met the following requirements:

Node.js: Make sure you have Node.js installed on your machine. You can download it from https://nodejs.org/.
npm: npm is the package manager for Node.js and should be included with your Node.js installation.

## Setup Instructions
Follow these steps to set up and run the Car Management System app on your local machine:

1. Download and unzip project file: 
   Download the 'Internship-Project' file and then unzip

2. Navigate to the Project Directory:
   Change your current directory to the project's root folder: cd car-management-system

3. Install Dependencies:
   Use npm to install the project's dependencies: npm install

4. Start the Development Server:
   Navigate to the folder containing the backend: cd backend 
   Start the development server by running the following command: npm start
   
5. Access the App:
   Navigate to the folder containing the frontend: cd frontend 
   Start the application by running the following command: npm start

6. Use the App:
   You can interact with the app by adding, updating, and deleting clients and their cars on the Clients and Cars pages.

7. Stop the Development Server:
   To stop the development server, press Ctrl + C in your terminal.

## API Configuration
The app uses a local API server for managing clients and cars. The API server is already configured to run locally on port 8800. If you need to modify the API endpoints or settings, you can update them in the following files:

src/pages/ClientsPage.js: Update API endpoints for clients.
src/pages/CarsPage.js: Update API endpoints for cars.
Make sure to restart the development server after making any changes to the API configuration.

## Technologies Used
- React: The app is built using React, a popular JavaScript library for building user interfaces.
- React Bootstrap: React Bootstrap components are used for creating a responsive and visually appealing user interface.
- React Router: React Router is used for handling navigation and routing between different pages.
- Axios: Axios is used for making HTTP requests to the API server.
- Node.js: The local API server is built with Node.js.
- Express: Express is used as the web application framework for the API server.
