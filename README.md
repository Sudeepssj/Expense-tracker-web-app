# 💸 Expense Tracker Web Application

A modern full-stack Expense Tracker web application built using **Django, Bootstrap, AJAX, jQuery, and Chart.js**.  
The application helps users manage daily expenses, analyze spending patterns, and visualize financial data with interactive charts and analytics.

---

# 🚀 Features

## ✅ Authentication
- User Login & Logout
- Secure session handling

## ✅ Expense Management
- Add new expenses
- Edit expenses using AJAX modal
- Delete expenses instantly
- Dynamic category selection
- Add custom categories

## ✅ Expense Listing
- Real-time search filter
- Date range filtering
- AJAX-powered updates without page reload
- Responsive expense table

## ✅ Monthly Summary & Analytics
- Monthly expense summary
- Category-wise breakdown
- Interactive Pie Chart
- Interactive Bar Chart
- Chart toggle functionality
- Animated total expense counter
- Top spending category highlight

## ✅ Dashboard
- Clean responsive dashboard UI
- Quick navigation cards
- Modern card animations

## ✅ Dark Mode
- Persistent dark/light mode using localStorage
- Theme maintained across pages

## ✅ UI/UX Improvements
- Responsive design
- Bootstrap styling
- Smooth animations
- Toast notifications
- Hover effects
- Modern card layouts

---

# 🛠️ Technologies Used

## Backend
- Python
- Django

## Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- jQuery
- AJAX

## Data Visualization
- Chart.js

## Database
- SQLite3

---

# 📂 Project Structure

```bash
ExpenseTracker/
│
├── expense_tracker/
│
├── expenses/
│   ├── migrations/
│   ├── templates/
│   │   ├── add_expense.html
│   │   ├── dashboard.html
│   │   ├── expense_list.html
│   │   ├── monthly_summary.html
│   │   └── base.html
│   │
│   ├── static/
│   │   └── css/
│   │       └── style.css
│   │
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── forms.py
│
├── db.sqlite3
├── manage.py
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/expense-tracker.git
```

---

## 2️⃣ Navigate to Project Folder

```bash
cd expense-tracker
```

---

## 3️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 5️⃣ Run Migrations

```bash
python manage.py migrate
```

---

## 6️⃣ Create Superuser

```bash
python manage.py createsuperuser
```

---

## 7️⃣ Start Development Server

```bash
python manage.py runserver
```

---

# 🌐 Access Application

Open browser:

```bash
http://127.0.0.1:8000/
```

---

# 📊 Upcoming Features

- Yearly comparison charts
- Export reports to PDF
- Dashboard analytics cards
- User profile settings
- Category management system
- Advanced financial insights

---

# 📸 Screenshots

## Dashboard
- Responsive dashboard cards
- Dark mode support

## Expense List
- AJAX filtering
- Edit/Delete functionality

## Monthly Summary
- Interactive charts
- Category analytics

---

# 🧠 Learning Outcomes

This project demonstrates:
- Full-stack Django development
- AJAX integration
- Interactive chart visualization
- Dynamic DOM manipulation
- Responsive UI design
- CRUD operations
- Authentication system
- Dark mode implementation

---

# 👨‍💻 Author

**Sudeep Singh**

---

# 📄 License

This project is for educational and portfolio purposes.