# 🎓 Exam Hall Navigation Application

### A Smart Digital Solution for Examination Hall Identification

## 📌 About the Project

The **Exam Hall Navigation Application** is a Flutter-based mobile application developed to help students easily identify their allocated examination halls in educational institutions.

During examinations, students often face difficulties finding their examination halls, blocks, and floors using traditional notice boards and printed allocation lists.

This application provides a simple digital solution where students can enter their registration number and instantly retrieve their examination hall details.

The application also includes an administrator module to manage student examination hall allocation records using a centralized Supabase database.

## 🎯 Project Objectives

- To simplify the examination hall identification process.
- To provide quick access to student hall allocation details.
- To reduce dependency on printed notice boards.
- To minimize confusion and manual enquiries.
- To provide centralized student allocation management.
- To improve the examination experience for students.

## ✨ Features

### 👨‍🎓 Student Module
- Search examination hall using registration number.
- View allocated examination hall number.
- View examination floor details.
- Simple and user-friendly interface.
- Quick access to allocation information.

### 🔐 Admin Module
- Administrator authentication.
- Manage student hall allocation records.
- Upload and maintain allocation data.
- Centralized database management.

## 🛠️ Technologies Used

| Technology | Description |
|---|---|
| Flutter | Frontend mobile application development |
| Dart | Programming language |
| Supabase | Backend service |
| PostgreSQL | Database management |
| Visual Studio Code | Development environment |

## 🏗️ Application Modules

1. **Role Selection Module** – Allows users to select Student or Admin.
2. **Student Hall Finder** – Searches student allocation using registration number.
3. **Admin Authentication** – Provides secure administrator login.
4. **Hall Allocation Management** – Manages student hall allocation information.
5. **Database Integration** – Connects the application with Supabase.

## ⚙️ Working Process

1. The administrator logs into the application.
2. Student examination hall allocation details are maintained in the database.
3. The student opens the mobile application.
4. The student enters their registration number.
5. The application searches the Supabase database.
6. The allocated hall number and floor are displayed.

## 📂 Project Structure

```text
exam-hall-navigation-app/
│
├── android/
├── assets/
│   └── icon.png
│
├── lib/
│   └── main.dart
│
├── test/
│
├── pubspec.yaml
├── pubspec.lock
└── README.md
```

## 🚀 Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/exam-hall-navigation-app.git
```

### Step 2: Navigate to the Project Folder

```bash
cd exam-hall-navigation-app
```

### Step 3: Install Dependencies

```bash
flutter pub get
```

### Step 4: Configure Supabase

Add your Supabase project URL and API key in the application configuration.

```dart
await Supabase.initialize(
  url: 'YOUR_SUPABASE_URL',
  anonKey: 'YOUR_SUPABASE_ANON_KEY',
);
```

**Important:** Never upload service-role keys or other private credentials to GitHub. Use a secure configuration method for production.

### Step 5: Run the Application

```bash
flutter run
```

## 🗄️ Database Details

The application uses Supabase PostgreSQL for storing examination hall allocation information.

**Hall allocation table:** `Hall allocation`

Main fields:

| Column | Description |
|---|---|
| reg_no | Student registration number |
| student_name | Student name |
| hall_no | Allocated examination hall |
| floor | Examination hall floor |

The application also uses an `admins` table for administrator-related functionality.

## 🌟 Future Enhancements

- Interactive campus navigation maps.
- QR-code-based hall identification.
- Real-time examination notifications.
- Multiple examination session support.
- Multi-college and university integration.
- Improved administrator dashboard.

## 💡 Benefits

- Saves students' time.
- Reduces crowding near notice boards.
- Minimizes manual enquiries.
- Provides easy access to examination information.
- Reduces paper usage.
- Simplifies examination administration.

## 🎓 Project Information

| Category | Details |
|---|---|
| Project Name | Exam Hall Navigation Application |
| Project Type | Academic / Final-Year Project |
| Domain | Education Technology (EdTech) |
| Frontend | Flutter & Dart |
| Backend | Supabase |
| Database | PostgreSQL |

## 👩‍💻 Developed By

**Name:** Your Name

**College:** Your College Name

**Course:** Bachelor of Engineering (B.E.)

**Project:** Pre-Final year Academic Project

---

⭐ If you find this project interesting, feel free to explore the repository!

**Making examination hall identification easier through technology.**
