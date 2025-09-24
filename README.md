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

| File/Folder | Description |
| :--- | :--- |
| `index.php` | The main landing page. |
| `login.php` | User login interface. |
| `registration.php` | New user registration form. |
| `dashboard.php` | Logged-in user's main dashboard. |
| `prequest.php` | Form for submitting a new project request. |
| `quote-details.php` | View for detailed quote information. |
| `dbconnection.php` | Database configuration and connection script. |
| `admin/` | Contains all files and scripts for the **Admin Panel**. |
| `checklogin.php` | Script to process and verify login attempts. |
| `create-ticket.php` | Interface for users to create a support ticket (alternative to `prequest.php`). |
| `view-tickets.php` | User's view of submitted tickets/requests. |
| `manage-quotes.php` | Admin view to manage and update quotes. |
| `profile.php` | User's profile management page. |

---

## License

Open-source project under MIT License.
