# Inventory Manager

**Inventory Manager** is a Django-based web application that helps users manage and track product inventory efficiently. It allows adding, viewing, updating, and deleting products through a user-friendly interface.

## 🔑 Features

- Add new products
- View product list
- Update product details
- Delete products
- Responsive design using Bootstrap
- Form rendering with Django Crispy Forms

## 🛠 Tech Stack

- **Backend:** Django
- **Frontend:** Bootstrap 4
- **Forms:** Django Crispy Forms
- **Environment Management:** Pipenv

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/inventory-manager.git
cd inventory-manager
```

### 2. Activate virtual environment with Pipenv

```bash
pipenv install
pipenv shell
```

### 3. Run database migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 4. Run the development server

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser to access the app.

## 📦 Files

- `Pipfile` & `Pipfile.lock`: Manage project dependencies
- `manage.py`: Django management script
- `invApp/`: Contains the core inventory management app

## 👤 Author

**Emmanuel Ntihinyuka**
Tech Director | Software Engineer | Django Developer

---

### 💡 License

This project is open-source and available under the [MIT License](LICENSE).
