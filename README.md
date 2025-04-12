
# 📚 Weekly eBook Admin Dashboard

A web-based admin dashboard built for managing users, submissions, deadlines, and payments for an eBook platform. Built using **HTML**, **CSS**, **JavaScript**, and **Firebase** for backend services.

## ✨ Features

- 🔐 **Firebase Authentication** – Secure login/logout
- 🧑‍💼 **User Management** – Approve or remove users
- 📄 **Submission Tracking** – View and manage user submissions with real-time status updates (Approved, Rejected, Pending)
- 📊 **Analytics** – Dashboard with live stats on users, submissions, and payment status
- 📆 **Set Submission Deadline** – Admins can update the submission deadline
- 💳 **Payment Tracking** – Track weekly or monthly payments for each user
- 📈 **Live Firebase Integration** – Real-time updates with Firestore

## 🖥️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Firebase (Authentication & Firestore)
- **Charting (optional)**: Chart.js (on `analytics.html`)

## 📁 Project Structure

```
📦 weekly-ebook-admin
├── assets/
│   └── logo.png              # Your platform's logo
├── index.html                # Login page
├── admin.html                # Admin dashboard
├── analytics.html            # Admin analytics page
├── style.css (optional)      # For external CSS (currently inline in HTML)
├── README.md                 # You're reading it!
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weekly-ebook-admin.git
   cd weekly-ebook-admin
   ```

2. Set up your **Firebase Project**:
   - Go to [Firebase Console](https://console.firebase.google.com/)
   - Create a new project
   - Enable **Authentication** (Email/Password)
   - Set up **Firestore Database**
   - Copy your Firebase config and replace it inside the `<script>` tag in your HTML

3. Launch locally:
   Just open `admin.html` or `index.html` in your browser.

> ⚠️ Make sure you’re logged in with a Firebase user who has admin privileges.

## ✅ To Do

- [ ] Add role-based access for admin vs users
- [ ] Add responsive mobile support
- [ ] Enhance analytics with more graphs
- [ ] Add file upload support for submissions (e.g. PDFs)

## 🛡️ License

This project is open-source and available under the [MIT License](LICENSE).

---

Feel free to fork, star, and contribute! ❤️  
```

---
