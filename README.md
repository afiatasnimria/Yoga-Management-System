# 🧘 Yoga Center Management System  
### 🌐 Web Programming-Based Project

A complete web-based management system developed to handle the daily operations of a yoga center efficiently.  
This application digitalizes administrative tasks such as member management, trainer assignment, class scheduling, attendance tracking, and payment records.

---

## 📖 Project Description

The **Yoga Center Management System** is designed to simplify and automate yoga center operations.  
Instead of maintaining manual records, this system provides a centralized digital platform for managing members, trainers, classes, and payments.

It improves operational efficiency, reduces errors, and enhances the overall user experience.

---

## ✨ Core Features

### 🔐 Admin Module
- Add, update, delete members
- Add and manage trainers
- Create and manage yoga classes
- Assign trainers to classes
- Monitor attendance records
- Track membership payments
- View dashboard statistics

### 👤 Member Module
- Member registration
- View class schedules
- Check membership details
- View attendance history
- Track payment status

### 👩‍🏫 Trainer Module
- View assigned classes
- Access member list
- Update attendance records

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| HTML | Structure |
| CSS | Styling |
| JavaScript | Client-side interactivity |
| PHP | Backend logic |
| MySQL | Database management |
| XAMPP | Local development server |

---

## 🗂️ Project Structure

```
Yoga-Center-Management/
│
├── admin/
│   ├── dashboard.php
│   ├── manage_members.php
│   └── manage_trainers.php
│
├── member/
│   └── member_dashboard.php
│
├── trainer/
│   └── trainer_dashboard.php
│
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
├── config.php
├── index.php
└── database.sql
```

---

## 🗄️ Database Tables

- `admins`
- `members`
- `trainers`
- `classes`
- `attendance`
- `payments`

---

## ⚙️ Installation & Setup

### Step 1: Install Requirements
- Install **XAMPP** or any local server with PHP & MySQL.

### Step 2: Clone the Repository
```bash
git clone https://github.com/your-username/Yoga-Center-Management.git
```

### Step 3: Move Project
Copy the project folder into:
```
C:/xampp/htdocs/
```

### Step 4: Database Setup
1. Open **phpMyAdmin**
2. Create a database named `yoga_center`
3. Import `database.sql`

### Step 5: Configure Database Connection
Update `config.php`:

```php
$host = "localhost";
$dbname = "yoga_center";
$username = "root";
$password = "";
```

### Step 6: Run the Project
Start Apache and MySQL from XAMPP.

Open your browser:
```
http://localhost/Yoga-Center-Management/
```

---

## 🎯 Project Objectives

- Automate yoga center management
- Reduce paperwork
- Maintain accurate records
- Improve administrative efficiency
- Enhance member experience

---

## 🔮 Future Enhancements

- Online payment gateway integration
- Email & SMS notifications
- Advanced analytics dashboard
- Responsive mobile-friendly UI
- Multi-branch management support
- Role-based authentication system

---

## 📸 Screenshots

*(Add screenshots of your project interface here)*

---

## 🤝 Contribution

Contributions are welcome!  
Feel free to fork this repository and submit a pull request.

---

## 👩‍💻 Author

Developed as a Web Development Project.

---

## 📄 License

This project is created for educational purposes.
