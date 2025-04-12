
# 🏨 Hostel Management System

A web-based Hostel Management System built using **HTML**, **CSS**, **JavaScript**, **PHP**, and **MySQL**. This project is designed to help manage hostel-related operations like student registrations, room allotments, payment tracking, and admin control.



## 🔧 Features

- 🧑‍🎓 Student Registration & Login  
- 🏠 Room Allotment  
- 💵 Fee/Payment Management  
- 📋 Admin Dashboard  
- 📂 View Allocated Rooms & History  
- 🔐 Authentication and Session Management  
- 📊 Responsive UI with HTML, CSS, and JavaScript  



## 🛠️ Tech Stack

| Technology | Use |
|------------|-----|
| HTML       | Frontend structure |
| CSS        | Styling and layout |
| JavaScript | Form validation and interactivity |
| PHP        | Server-side scripting |
| MySQL      | Database management |



## 📁 Project Structure


hostel-management-system/
│
├── assets/              # CSS, JS, and image files
├── db/                  # Database connection script
├── includes/            # Header, footer, sidebar, etc.
├── student/             # Student-specific pages
├── admin/               # Admin dashboard and controls
├── index.php            # Landing page
├── login.php            # Login system
├── register.php         # Student registration
├── room-allotment.php   # Room assignment logic
└── README.md            # This file


## ⚙️ Setup Instructions

1. **Clone the repository**

  ## ⚙️ Setup Instructions

1. **Clone the repository**

   bash
   git clone https://github.com/patushinde14/Hostel_Management_System.git
   cd Hostel_Management_System


2. **Create the database**

   - Import the `hostel.sql` file into your MySQL server using phpMyAdmin or MySQL CLI.

3. **Configure the database connection**

   - Open `db/config.php` and update your DB credentials:

    php
     $host = 'localhost';
     $user = 'root';
     $pass = '';
     $dbname = 'hostel_db';
     ```

4. **Run the project**

   - Place the project folder in your XAMPP/WAMP `htdocs` directory.
   - Start Apache and MySQL from your control panel.
   - Visit: `http://localhost/hostel-management-system`



## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.



## 📜 License

This project is open-source and available under the [MIT License](LICENSE).



## 💬 Acknowledgments

- Open-source libraries
- Font Awesome / Iconify
- Inspiration from college hostel systems
