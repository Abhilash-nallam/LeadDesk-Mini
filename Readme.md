# LeadDesk Mini

> **Digital Heroes Internship -- Full Stack Development Task**

LeadDesk Mini is a production-ready Full Stack Lead Management (Mini
CRM) web application developed as part of the **Digital Heroes
Internship Qualification Task**. It allows visitors to submit enquiries
through a modern landing page while providing administrators with a
secure dashboard to manage and track leads.

------------------------------------------------------------------------

# 🚀 Live Project

-   **Live Demo:** https://naportfolio.gt.tc/Task/
-   **Admin Login:** https://naportfolio.gt.tc/Task/admin/login.php
-   **Repository:** [https://github.com/abhilash-nallam](https://github.com/Abhilash-nallam/LeadDesk-Mini)

------------------------------------------------------------------------

# 📌 Project Overview

LeadDesk Mini demonstrates a complete end-to-end CRM workflow.

Visitors can:

-   Submit enquiries
-   Select a budget range
-   Send messages

Administrators can:

-   Securely log in
-   View all leads
-   Search leads
-   Update lead status
-   Delete leads
-   Track statistics

------------------------------------------------------------------------

# ✨ Features

## Public Website

-   Responsive landing page
-   Hero section
-   Services section
-   Why Choose Us
-   Testimonials
-   Pricing plans
-   Contact / Lead form
-   Client & server-side validation
-   Responsive design

## Admin Dashboard

-   Secure Login
-   Session Authentication
-   Dashboard Statistics
-   Search Leads
-   AJAX Status Update
-   Delete Lead
-   Logout

------------------------------------------------------------------------

# 🔐 Security

-   PDO Prepared Statements
-   Password Hashing (`password_hash`, `password_verify`)
-   Session Protection
-   CSRF Protection
-   Input Validation
-   SQL Injection Prevention

------------------------------------------------------------------------

# 🛠 Tech Stack

## Frontend

-   HTML5
-   CSS3
-   Bootstrap 5
-   JavaScript

## Backend

-   PHP 8

## Database

-   MySQL

------------------------------------------------------------------------

# 📂 Folder Structure

``` text
LeadDeskMini/
│
├── admin/
├── api/
├── css/
├── database/
├── images/
├── includes/
├── js/
├── index.php
└── README.md
```

------------------------------------------------------------------------

# ⚙ Installation

1.  Upload the project files.
2.  Create a MySQL database.
3.  Import `database/leaddesk.sql`.
4.  Update `includes/db.php`:

``` php
define('DB_HOST','sql209.infinityfree.com');
define('DB_NAME','if0_40226469_leaddesk');
define('DB_USER','if0_40226469');
define('DB_PASS','YOUR_MYSQL_PASSWORD');
```

5.  Open:

```{=html}
<!-- -->
```
    https://yourdomain.com/admin/login.php

------------------------------------------------------------------------

# 🗄 Database

Tables:

-   admins
-   leads

Imported using phpMyAdmin on InfinityFree.

------------------------------------------------------------------------

# 🔑 Demo Credentials

Username:

    admin

Password:

    Admin@123

------------------------------------------------------------------------

# 🌐 Deployment

Successfully deployed on InfinityFree.

Deployment process included:

-   Creating a new MySQL database
-   Updating database credentials
-   Importing SQL schema
-   Fixing database name mismatch
-   Importing admin and lead tables
-   Testing authentication
-   Verifying dashboard functionality
-   End-to-end lead submission testing

------------------------------------------------------------------------

# ✅ Completed Functionality

-   Landing Page
-   Lead Form
-   Database Storage
-   Admin Login
-   Dashboard
-   Lead Statistics
-   Search
-   Status Update
-   Delete Lead
-   Responsive Layout

------------------------------------------------------------------------

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/4be20e1a-fcbd-4e77-83f5-f51cb3f78894" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/aefa390f-d6f2-4e3c-9c59-48d5bb319c00" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/61461be5-5e0e-43ba-8d17-74d96eb503f7" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/c74e15ed-fa07-443a-95bc-b9924bf9e122" />

------------------------------------------------------------------------

# 🔮 Future Improvements

-   Multiple Admin Roles
-   Email Notifications
-   CSV Export
-   Analytics Dashboard
-   Lead Assignment
-   Activity Logs
-   Two-Factor Authentication

------------------------------------------------------------------------

# 👨‍💻 Developer

**Abhilash Nallam**

Engineering Student

------------------------------------------------------------------------

# 🙏 Acknowledgements

Built for the **Digital Heroes Internship Qualification Task**.

Special thanks to the Digital Heroes team for providing a practical Full
Stack Development challenge.
