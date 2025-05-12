# 🖥️ Django Web Application

A full-stack Django web application designed to provide dynamic, data-driven functionality, utilizing SQL for backend data management, Django's powerful ORM, and HTML for frontend presentation.

## 🚀 Features
- 🧠 **Backend Logic** powered by Django
- 🔐 **Persistence** using SQL for database management
- ⚙️ **Dynamic Content Rendering** with Django Templates
- 📊 **Data Handling** via Django ORM
- 📱 **Responsive frontend** with HTML and CSS

## 🧱 Tech Stack
- Python 3.x
- Django
- SQL 

## 📁 Project Structure
```bash
DjangoProject/
├── DjangoProject/          # Main Django project configuration (settings, urls, wsgi)
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── phone_app.py               # Django management script
├── main/                   # Main application: views, models
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── tests.py
│   ├── models.py
│   └── views.py
│   └── view_queries.py
├── templates.py/               # templates for each page
│   ├── AddApplication.html/
│   ├── InstallApplication.html/
│   ├── RemoveApplication.html/
│   ├── index.html/
│   ├── queryResults.html/
```

## ⚙️ **Getting Started**
1. **Clone the repository**:

   git clone https://github.com/Cohen-inbal/Django-Project.git
    cd Django-Project

2. **Run the development server using the Django management script:**
 
    python phone_app.py runserver


3. **Access the website**:

    After running the server, a local development URL will appear in your terminal.
    Open it in your browser to start using the app.



