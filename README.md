# PiCloud Storage

PiCloud Storage is a simple cloud‑storage style web application where users can upload, manage, and access their files through a clean Django interface.

---

## 📁 Project Structure

```
PiCloud-Storage/
│
├── cloud_storage/               
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
├── accounts/                   
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py                
│   ├── views.py                 
│   ├── urls.py
│   ├── forms.py
│   ├── templates/
│       ├── register.html
│       ├── login.html
│       ├── profile.html
│
├── storage/                   
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py               
│   ├── views.py  
│   ├── urls.py
│   ├── templates/
│       ├── dashboard.html
│
├── templates/
│   ├── add_payment_method.html
│   ├── checkout.html
│   ├── payment_methods.html
│   ├── privacy.html
│   ├── security.html
│   ├── subscriptions.html
│   ├── support.html
│   ├── terms.html
│
├── media/
│   ├── user_1/
│   ├── user_2/
│       ├── ... (user uploaded files)
│
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md

```

---

## ▶️ How to Run the Project

### 1. Clone the Repository

```
git clone https://github.com/Rajshigavan/PiCloud-Storage.git
cd PiCloud-Storage
```

### 2. Create Virtual Environment

```
python -m venv venv
```

#### Activate:

**Windows**

```
venv\Scripts\activate
```

**Mac / Linux**

```
source venv/bin/activate
```

---

### 3. Install Dependencies

```
pip install -r requirements.txt
```

---

### 4. Apply Migrations

```
python manage.py makemigrations
```

---

### 5. Apply Migrations

```
python manage.py migrate
```

------

### 6. Create Superuser (Optional)

```
python manage.py createsuperuser
```

---

### 7. Run the Server

```
python manage.py runserver
```

---

### . Access the App

```
http://127.0.0.1:8000/
```

---

Your PiCloud Storage project is now up and running locally.
