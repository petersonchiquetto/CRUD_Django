# Space Django 🐍

This project is a CRUD (Create, Read, Update, Delete) application developed with Django. It allows you to manage records in a database simply and efficiently.

📌 **Features**
* Create new records
* List existing records
* Update records
* Delete records

🛠 **Technologies Used**
* Django - Python web framework
* SQLite - Default database
* Bootstrap - For front-end styling

📦 **Installation**

1️⃣ Clone this repository:

```bash
git clone [https://github.com/petersonchiquetto/SpaceDjango.git](https://github.com/petersonchiquetto/SpaceDjango.git)
cd CRUD_Django
```

2️⃣ Create a virtual environment (optional, but recommended):

```bash
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate      # For Windows
```

3️⃣ Install the dependencies:

```bash
pip install -r requirements.txt
```

4️⃣ Run the database migrations:

```bash
python manage.py migrate
```

5️⃣ Start the server:

```bash
python manage.py runserver
```

Access in your browser: http://127.0.0.1:8000/

📝 **How to Use**
1. Access the application through your web browser.
2. Use the interface to add, view, edit, and delete records.
3. Enjoy the CRUD functionality integrated with Django!

📂 **Project Structure**

```
CRUD_Django/
├── myapp/                # Main Django application
│   └──...
├── templates/            # HTML files
│   └──...
├── static/               # Static files (CSS, JS)
│   └──...
├── db.sqlite3            # SQLite database (automatically generated)
├── manage.py             # Django management file
└── requirements.txt      # Project dependencies
```

📜 **License**

This project is under the MIT License.
