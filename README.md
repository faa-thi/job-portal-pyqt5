# Job Portal Application (PyQt5)

A desktop-based Job Portal application developed using Python and PyQt5. This application allows users to log in as employees or employers and manage job-related activities through an interactive GUI.

---

## 🚀 Features

* Employee and Employer login system
* Job listings and application management
* Apply for jobs functionality
* User authentication using SQLite database
* GUI-based interface built with PyQt5

---

## 🛠 Tech Stack

* **Language:** Python
* **GUI Framework:** PyQt5
* **Database:** SQLite
* **Tools:** DB Browser for SQLite

---

## 📁 Project Structure

```text
Job_portal/
│── homepage.py            # Main entry point (START HERE)
│── login.py
│── employee_login.py
│── employer_login.py
│── employee_page.py
│── employer_page.py
│── job_listings.py
│── apply.py
│── applicants.py
│── update.py
│── job_portal.db         # SQLite database
│── *.ui                  # UI design files
```

---

## ▶️ How to Run

1. Make sure Python is installed
2. Install required library:

```bash
pip install PyQt5
```

3. Run the application:

```bash
python homepage.py
```

👉 **Important:** Start the application using `homepage.py` to open the main portal.

---

## 🗄 Database

* SQLite database used for storing all data
* Tables include:

  * `employee_login`
  * `employer_login`
  * `job_listings`
  * `applicant`

---

## 🔐 Sample Login Credentials

Use credentials stored in the database (example):

* **Username:** [nawfa@gmail.com](mailto:nawfa@gmail.com)
* **Password:** abc123

---

## ⚠️ Notes

* Ensure correct database path is configured in the code
* Do not delete `.ui` files (required for GUI)
* Ignore `__pycache__` folder when uploading to GitHub

---

## 👩‍💻 Author

**Faathima Nawfa B**

---
