HANDICRAFT NEPAL ONLINE STORE - ASSESSMENT 4 DYNAMIC WEBSITE
============================================================

This is an upgraded dynamic PHP/MySQL version of the previous static website.
It includes the missing Assessment 4 requirements: database, forms, validation,
login/register, access control, admin dashboard, SEO, accessibility and privacy page.

TECHNOLOGY USED
---------------
- PHP
- MySQL
- HTML/CSS/JavaScript
- XAMPP / phpMyAdmin
- VS Code

HOW TO RUN IN XAMPP
-------------------
1. Extract this folder.
2. Copy the full folder named "handicraft_nepal_assessment4" into:
   C:\xampp\htdocs\

3. Start XAMPP Control Panel.
4. Start Apache.
5. Start MySQL.

6. Open phpMyAdmin:
   http://localhost/phpmyadmin

7. Click Import.
8. Select this file:
   database/handicraft_store.sql

9. Click Go.
   This will create the database: handicraft_store_db

10. Open the website:
   http://localhost/handicraft_nepal_assessment4/

DATABASE CONFIGURATION
----------------------
The database connection file is:
includes/config.php

Default settings:
DB_HOST = localhost
DB_NAME = handicraft_store_db
DB_USER = root
DB_PASS = empty password

For normal XAMPP installation, this should work without changes.

TEST LOGIN ACCOUNTS
-------------------
Admin account:
Email: admin@handicraftnepal.com
Password: Admin@123

Customer account:
Email: customer@example.com
Password: Customer@123

ADMIN DASHBOARD
---------------
After logging in as admin, open:
http://localhost/handicraft_nepal_assessment4/admin/dashboard.php

Admin can manage:
- products
- orders
- contact messages
- users
- testimonials/reviews

CUSTOMER FEATURES
-----------------
Customer can:
- register account
- login/logout
- browse products
- add products to cart
- checkout/place order
- view order history
- contact the store

ASSESSMENT 4 REQUIREMENT CHECKLIST
----------------------------------
HTML/CSS layout: completed
Web media/images: completed
Forms: completed
Error handling and validation: completed
MySQL database: completed
Server-side authentication: completed
Access control: completed
Admin dashboard: completed
SEO meta tags: completed
Accessibility basics: completed
Privacy/GDPR page: completed
Report notes included in docs folder

IMPORTANT NOTE
--------------
This is an academic prototype. It does not process real payments.


IMPORTANT UPDATE
----------------
This final version includes 20 seeded products with corrected local illustrative images.
If you already imported an older database version, re-import database/handicraft_store.sql to refresh the product list.

LATEST VISUAL UPDATE
--------------------
This version replaces the placeholder artwork with better-looking AI-generated product photos across the site.
Please re-import database/handicraft_store.sql (or database/refresh_products_only.sql) so the new image paths and full 20-product catalogue appear correctly.
