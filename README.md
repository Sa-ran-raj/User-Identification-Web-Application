# 🧑‍💼 User Identification System

A feature-rich Flask-based web application that enables user registration, authentication, profile management, note-taking, QR code login, and password reset via email. The backend is powered by MongoDB, and the UI is built with HTML, CSS, and Bootstrap for responsive design.

---

## 🚀 Features

### 🔐 User Authentication
- Sign up with profile photo upload and personal details
- Secure password hashing using `werkzeug.security`
- Login with credentials or QR code
- Session-based user login management
- Logout functionality

### 🧾 Notes Section
- Users can create and update personal notes
- Each note is timestamped with the last updated time

### 👤 User Profile
- View and update profile information
- Age is auto-calculated from date of birth
- Base64-encoded profile photo storage
- Visual display of profile completion percentage

### 📸 QR Code Authentication
- Auto-generated QR codes for quick login
- Users can scan the QR code to login securely

### 📧 Password Reset via Email
- Forgot password feature with email verification
- Secure password reset links with token expiration
- Email integration using Flask-Mail

### 📊 Dashboard
- Displays profile details and notes
- Profile completeness progress bar
- User-friendly interface with Bootstrap styling

---

## 🛠️ Technologies Used

| Stack        | Tools/Frameworks                                    |
|--------------|------------------------------------------------------|
| Backend      | Flask, Werkzeug, PyMongo                             |
| Frontend     | HTML, CSS, Bootstrap                                 |
| Database     | MongoDB                                              |
| Security     | Password Hashing, Sessions, Token-Based Reset Links |
| Image Upload | Base64 Encoding for Profile Photos                   |
| QR Code      | `qrcode` Python Library                              |
| Email        | Flask-Mail                                           |

---
