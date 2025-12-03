
# MyWebsite – Django Project

This is a simple Django web application created for learning and development purposes.  
It includes basic features like user registration, login, and a sample homepage.

---

## 🚀 Features

- User Registration  
- User Login / Logout  
- Django Admin Panel  
- Basic project structure  
- Easy to extend and customize  

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Django 5.x**
- **HTML / CSS**
- **SQLite3 Database**

---

## 📦 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/SrinivasNaren/mywebsite.git
cd mywebsite
````

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations

```bash
python manage.py migrate
```

### 5. Run the Development Server

```bash
python manage.py runserver
```

Open the browser and go to:

```
http://127.0.0.1:8000/
```

---

## 📁 Project Structure

```
mywebsite/
│── mywebsite/       # Main project settings
│── app/             # Your Django app (if created)
│── manage.py        # Entry point for Django commands
│── templates/       # HTML templates (if added)
│── static/          # CSS, JS, images (if added)
```

---

## 🔑 Admin Access

Create a superuser:

```bash
python manage.py createsuperuser
```

Visit:

```
http://127.0.0.1:8000/admin/
```

---

## 🙌 Contributing

You can fork this project and add new features, fix bugs, or improve UI.

---

## 📄 License

This project is open-source and free to use.

