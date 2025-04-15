# 🔗 LinkMitra

**LinkMitra** is a simple, fast, and elegant URL shortener built using Django. It converts long, cluttered URLs into short, manageable links—perfect for easy sharing on social media, emails, or messaging apps.

This project was developed with the intent to learn and apply Django fundamentals while creating something useful and deployable. ✨

---

## 🚀 Features

- Shorten any long URL into a compact link
- Clean and user-friendly interface
- Easy to deploy and maintain
- Built with Django and Python
- Minimal and lightweight

---

## 🛠 Installation Guide

Follow these steps to set up the project locally:

### 1. Create a Project Folder

```bash
mkdir LinkMitra
cd LinkMitra
```

### 2. Set Up Virtual Environment

Install `virtualenv` if you haven't already:

```bash
pip install virtualenv
```

Create and activate the virtual environment:

#### For Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

#### For macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Clone the Repository

```bash
git clone <your-repo-url>
cd URL-Shortener
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Development Server

#### For Windows:
```bash
python manage.py runserver
```

#### For macOS/Linux:
```bash
python3 manage.py runserver
```

Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) to access the app in your browser.

---

## 📁 Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS (custom styled)
- **URL Handling:** pyshorteners (with optional integration)
