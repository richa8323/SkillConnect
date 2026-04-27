# SkillConnect 🔗

A Django REST Framework-based web application that connects people through skills.

---

## 🛠️ Tech Stack

- **Backend:** Python, Django 6.0
- **API:** Django REST Framework
- **Database:** SQLite3
- **Environment:** Python Virtual Environment (venv)

---

## ⚙️ Prerequisites

Make sure you have the following installed:

- [Python 3.8+](https://www.python.org/downloads/)
- [VS Code](https://code.visualstudio.com/) (recommended)
- pip (comes with Python)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/SkillConnect.git
cd SkillConnect
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

**Windows (PowerShell):**
```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
.\venv\Scripts\Activate.ps1
```

**Windows (CMD):**
```cmd
venv\Scripts\activate
```

**Mac/Linux:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install django djangorestframework
```

> If a `requirements.txt` is available:
> ```bash
> pip install -r requirements.txt
> ```

### 5. Apply Migrations

```bash
cd SkillConnectProject
python manage.py migrate
```

### 6. Create a Superuser (Optional)

```bash
python manage.py createsuperuser
```

### 7. Run the Development Server

```bash
python manage.py runserver
```

Now open your browser and visit:
```
http://127.0.0.1:8000/
```

---

## 📁 Project Structure

```
SkillConnectProject/
│
├── skillconnect/          # Main Django project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── manage.py              # Django management utility
├── db.sqlite3             # SQLite database
└── .gitignore
```

---

## 🌐 Available URLs

| URL | Description |
|-----|-------------|
| `http://127.0.0.1:8000/` | Home Page |
| `http://127.0.0.1:8000/admin/` | Django Admin Panel |
| `http://127.0.0.1:8000/api/` | REST API Endpoints |

---

## 🔒 Environment Variables

Create a `.env` file in the root directory:

```env
SECRET_KEY=your-secret-key-here
DEBUG=True
```

> ⚠️ Never commit your `.env` file to GitHub. It is already listed in `.gitignore`.

---

## 📦 Generate requirements.txt

To save all installed packages for others:

```bash
pip freeze > requirements.txt
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
