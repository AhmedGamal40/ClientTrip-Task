# Project Title: Angular PDF Manager

## Clone the repository:
1- git clone https://github.com/AhmedGamal40/ClientTrip-Task
2- cd angular-pdf-manager
3- npm install
4- ne serve

## Overview
Angular PDF Manager is a web application built using the Angular framework. It allows users to log in, manage PDF files, and view uploaded PDFs. The project demonstrates proficiency in Angular, including routing, services, component interaction, form validation, and Tailwind CSS for styling.

## Features
- **User Authentication:** Users can log in and out, with authentication managed by a custom `AuthService`.
- **PDF Management:** Users can upload, view, and remove PDF files. The application uses `localStorage` to persist data across sessions.
- **Responsive Design:** The application is styled with Tailwind CSS, ensuring a responsive and modern user interface.
- **Role-Based Routing:** Protected routes ensure that only authenticated users can access the Home and Dashboard pages.

## Project Structure
The project follows the standard Angular project structure, with components, services, and guards organized into appropriate directories.

- **src/app/components**: Contains the Angular components such as `LoginComponent`, `HomeComponent`, and `DashboardComponent`.
- **src/app/services**: Contains services like `AuthService` for managing authentication and `DataService` for handling PDF data.
- **src/app/guards**: Contains `AuthGuard` to protect routes from unauthorized access.
- **src/app/app-routing.module.ts**: Defines the application’s routes, including the protected routes.

## Getting Started
### Prerequisites
- **Node.js**: Ensure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).
- **Angular CLI**: Install Angular CLI globally using npm:
```bash
npm install -g @angular/cli

### Usage
Login
Use the following credentials to log in:
Email: ahmed.gamal.xv@gmail.com
Password: 123456

## Uploading PDFs
Navigate to the Home page.
Click on the "Choose File" button and select a PDF from your computer.
The uploaded PDF will be displayed in the list with options to open or remove it.