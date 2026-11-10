# CV Darul Management System

Web-based Inventory and Operational Management Information System for CV Darul.

This project is developed as a Final Project for the Software Engineering course (Implementasi Perangkat Lunak/IPL) at Universitas Jenderal Achmad Yani.

## About The Project

CV Darul Management System is a web-based information system designed to help manage inventory, wedding organizer orders, logistics operations, scheduling, fleet management, and company finances.

The system aims to improve operational efficiency, reduce manual recording errors, and centralize business information within one integrated platform.

## Tech Stack

**Frontend**
- HTML
- CSS
- Bootstrap

**Backend**
- PHP
- Laravel

**Database**
- MySQL

## Main Features

- User Authentication and Role-Based Access Control (RBAC)
- Dashboard and Operational Overview
- Inventory and Warehouse Management
- Wedding Organizer and Order Management
- Logistics Scheduling
- Fleet Tracking
- Invoice and Payment Management
- Operational Reports

## User Roles

- Admin
- Manager
- Owner
- Finance
- Employee / Field Crew
- Customer / Wedding Organizer

## Project Structure

The application follows Laravel's MVC (Model-View-Controller) architecture.

- `app/` - Application logic, models, and controllers.
- `database/` - Database migrations and seeders.
- `resources/views/` - Application user interfaces.
- `public/` - Public assets such as CSS, JavaScript, and images.
- `routes/` - Application routing configuration.
- `docs/` - Software requirements and design documentation.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kyyfirmannn/cv-darul-management-system.git
   ```

2. Navigate to the project directory:

   ```bash
   cd cv-darul-management-system
   ```

3. Install dependencies:

   ```bash
   composer install
   ```

4. Copy the environment configuration:

   ```bash
   cp .env.example .env
   ```

   On Windows, you can use:

   ```powershell
   Copy-Item .env.example .env
   ```

5. Generate the application key:

   ```bash
   php artisan key:generate
   ```

6. Configure your database connection in the `.env` file.

7. Run database migrations:

   ```bash
   php artisan migrate
   ```

8. Start the development server:

   ```bash
   php artisan serve
   ```

9. Open the application:

   ```text
   http://127.0.0.1:8000
   ```

## Project Documentation

The project is designed based on the following documents:

- Software Requirements Specification (SRS)
- Software Design Document (SDD)

Both documents are available in the `docs/` directory.

## Development Team

**Group 4 – Informatics Study Program**

Universitas Jenderal Achmad Yani

Academic Year 2026

## Project Status

Under Development.