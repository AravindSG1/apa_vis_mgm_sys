# 🏢 Apartment Visitors Management System

A web application built using **Python**, **Django**, **HTML**, **CSS**, and **JavaScript** for efficient management and tracking of apartment visitors. This system supports detailed visitor logging, pass issuance for frequent visitors (e.g. milkmen, newspaper vendors), and provides a user-friendly dashboard for monitoring.

---

## 🚀 Features

- **Visitor Logging**
  - Track guest entry and exit
  - Real-time and historical data access

- **Pass Management**
  - Generate and validate passes for regular visitors
  - Avoids redundant data entry

- **Responsive UI**
  - Clean interface for security staff
  - Designed using HTML, CSS, JavaScript

- **Django Admin**
  - Use Django’s built-in admin for backend data control

---

## 🛠️ Tech Stack

- **Backend**: Python, Django  
- **Frontend**: HTML, CSS, JavaScript  
- **Database**: SQLite (default)  
- **ORM**: Django ORM  

---

## 📁 Folder Structure

├── apa_vis_mgm_sys/  
├── app1/  
├── static/  
├── templates/  
├── db.sqlite3  
├── manage.py  
├── requirements.txt  


---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```
   git clone https://github.com/AravindSG1/apa_vis_mgm_sys
   cd apartment-visitors-management
   ```

2. **Create a virtual environment**
    ```
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install dependencies**
    `pip install -r requirements.txt`

4. **Apply migrations**
    `python manage.py migrate`

5. **Run the server**
    `python manage.py runserver`

6. **Open in browser**
    Visit: `http://127.0.0.1:8000/`