# UI Law Firm Document Management System (DMS)

## Overview
A web-based document management system built with PHP and MySQL to organize, store, and manage legal documents and user access workflows for a law firm.

## Live Deployment
- **Live Application:** [https://lawfirm-dms.page.gd/login.php](https://lawfirm-dms.page.gd/login.php)
- **Hosting Platform:** InfinityFree (PHP & MySQL)

## Demonstration Accounts
Use the following pre-configured accounts created by the installer to test role-based access on the live application[cite: 3]:

| Role | Username | Password |
| :--- | :--- | :--- |
| Administrator | `admin` | `Admin@123`[cite: 3] |
| Legal Secretary | `secretary` | `Secretary@123`[cite: 3] |
| Lawyer | `lawyer1` and `lawyer2` | `Lawyer@123`[cite: 3] |
| Client | `client1` and `client2` | `Client@123`[cite: 3] |

## Key Features
- User authentication and role-based access control (Administrator, Legal Secretary, Lawyer, Client)[cite: 3]
- Document upload, categorization, search, and management
- Activity and audit logging for key system actions

## Tech Stack
- **Backend:** PHP[cite: 2]
- **Database:** MySQL

## Project Structure
- `login.php` — Entry point / user authentication page[cite: 2]
- `dashboard.php` — Main user workspace after authentication[cite: 2]
- `includes/` — Core configuration, database connection, and helper scripts[cite: 2]
- `*.sql` — Database schema and initial data export

## Setup & Deployment Notes
1. Upload all project files to the web root (`htdocs` on InfinityFree).
2. Import the `.sql` database file via **phpMyAdmin**.
3. Update database connection credentials in the configuration file (e.g., `includes/bootstrap.php`) to match your hosting environment[cite: 2].
