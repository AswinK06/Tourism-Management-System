🧳 Tourism Management System (Wanderluxe)

A full-stack web application built to simplify travel booking for users and provide an efficient management dashboard for admins.
Users can explore tour packages, register, and book trips, while admins can manage packages, users, and bookings securely.

🚀 Features

🏝 Tour Package Listings – Browse destinations with details, images, and pricing.

📝 Booking System – Users can book packages and view their bookings.

🔐 User Authentication – Secure login and registration for users and admins.

🧑‍💼 Admin Panel – Manage packages, view bookings, and handle user accounts.

📱 Responsive Design – Optimized for desktop, tablet, and mobile devices.

🛠️ Tech Stack

| Layer    | Technology                       |
| -------- | -------------------------------- |
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Backend  | PHP (Procedural with PDO)        |
| Database | MySQL (RDBMS)                    |
| Server   | Apache (via XAMPP/WAMP)          |

📁 Project Structure

Tourism-Management-System/
├── admin/          # Admin dashboard files
├── includes/       # Config and helper files
├── user/           # User-specific pages
├── css/            # Stylesheets
├── js/             # JavaScript scripts
├── images/         # Static assets
├── index.php       # Landing page
└── ...
⚙️ Installation & Setup

Clone the Repository

git clone https://github.com/AswinK06/Tourism-Management-System.git

   Import Database

   Open phpMyAdmin.

   Create a database (e.g., wanderluxe).

   Import the provided .sql file.

   Configure Database Connection

   Open includes/config.php.

Update with your credentials:

   define('DB_HOST','localhost');
   define('DB_USER','root');
   define('DB_PASS','your_password');
   define('DB_NAME','wanderluxe');

Run the Project

   Place the project folder inside htdocs (XAMPP).

   Start Apache and MySQL from XAMPP Control Panel.

Open in browser:

   http://localhost/Tourism-Management-System/

🔮 Future Enhancements

   📱 Mobile app version.

   💬 Live chat support.

   🌐 Multilingual support (Tamil, Hindi, etc.).

   📊 Analytics dashboard for admin.

🙋‍♂️ Author

   Aswin K
   🎓 BE Computer Science Engineering
