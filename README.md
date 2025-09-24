# CRM System (PHP & MySQL)

A lightweight CRM system developed in **Core PHP** with **MySQL database**.  
The system allows **user management, project requests, and admin handling** with a simple Bootstrap-based interface.

---

## Features

- User registration & login  
- Admin authentication  
- Project request submission & tracking  
- Quote details with admin remarks  
- User login tracking (IP & session logs)

---

## Tech Stack

- PHP (Core)  
- MySQL / MariaDB  
- Bootstrap, jQuery, CSS  

---

## Setup

1. Import `crm.sql` into your MySQL database.  
2. Update credentials in `dbconnection.php`.  
3. Run the project on a local server (XAMPP/WAMP).  
4. Access via: `http://localhost/crm/`

---

## File Structure

- `index.php` → Landing page  
- `login.php` → User login  
- `registration.php` → User registration  
- `dashboard.php` → User dashboard  
- `prequest.php` → Project request form  
- `quote-details.php` → Quote detail view  
- `admin/` → Admin panel  
- `dbconnection.php` → Database connection file  

---

## License

Open-source project under MIT License.
