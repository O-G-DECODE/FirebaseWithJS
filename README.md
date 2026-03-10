# Firebase User Management (CRUD)

A simple web application that demonstrates **Firebase Authentication and Realtime Database CRUD operations** using **HTML, CSS, and JavaScript**.

Users can log in, add user details, edit them, and delete them from the Firebase Realtime Database.

---

## 🚀 Features

* Firebase Authentication (Login & Logout)
* Add user details (Name, Phone, Address)
* Display user list from Firebase Realtime Database
* Edit user information
* Delete user records
* Real-time database updates
* Simple and clean UI

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* Firebase Authentication
* Firebase Realtime Database

---

## 📂 Project Structure

```
project-folder
│
├── index.html      # Login page
├── dashboard.html  # User management page
├── style.css       # Styling
├── script.js       # Firebase and CRUD logic
└── README.md
```

---

## 🔧 Firebase Setup

1. Go to https://console.firebase.google.com/
2. Create a new Firebase project.
3. Enable **Authentication → Email/Password**.
4. Enable **Realtime Database**.
5. Copy your Firebase configuration.

Example:

```javascript
var firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  databaseURL: "YOUR_DATABASE_URL",
  projectId: "YOUR_PROJECT_ID"
};
```

6. Paste the config into your JavaScript file and initialize Firebase.

---

## ▶️ How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/your-repository-name.git
```

2. Open the project folder

```
cd your-repository-name
```

3. Open `index.html` in your browser.

---

## 📸 Application Flow

1. User logs in using Firebase Authentication.
2. After login, user is redirected to dashboard.
3. User can:

   * Add new users
   * View all users
   * Edit user details
   * Delete users
4. All changes update **in real-time** using Firebase Realtime Database.

---

## 🔒 Security Notes

* Firebase API keys should be stored in environment variables for production.
* Configure Firebase Database rules to restrict unauthorized access.

---

## 👨‍💻 Author

Developed as a practice project for learning **Firebase Authentication and CRUD operations**.

---

## ⭐ Future Improvements

* Better UI design
* Form validation
* Update form instead of using prompt
* Search functionality
* Pagination
