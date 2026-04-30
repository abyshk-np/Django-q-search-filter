#  Django Search & Filter App

A simple Django web application that allows users to **search posts** and **filter them by category**. This project demonstrates how to use Django’s ORM, templates, and query filtering using `Q` objects.

---

##  Features

*  Search posts by **title** and **content**
* Filter posts by **category**
* Combined search + category filtering
* Clean and simple backend logic

---

## Tech /Tools

* **Backend:** Django
* **Language:** Python
* **Database:** SQLite (default Django DB)
* **Frontend:** HTML (Django Templates)


---

##  How It Works

1. User enters a search term or selects a category
2. Data is sent via **GET request**:

   ```
   /?q=django&category=Tech
   ```
3. Django view processes request:

   * Filters posts using `icontains` (search)
   * Filters category using `iexact`
4. Filtered data is passed to template
5. Template dynamically renders results





---

##  Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Create virtual environment

```bash
python -m venv env
source env/bin/activate   # Linux/Mac
env\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install django
```

### 4. Run migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Run server

```bash
python manage.py runserver
```

---

##  Usage

* Open browser:

  ```
  http://127.0.0.1:8000/
  ```
* Try:

  * Searching keywords
  * Filtering categories
  * Combining both

---


---

## Contributing

Feel free to fork this project and improve it. Pull requests are welcome!

---


# Screenshots:
![Path Page](https://github.com/abyshk-np/Django-q-search-filter/blob/main/image/Screenshot%202026-04-28%20220548.png)
![Path Page](https://github.com/abyshk-np/Django-q-search-filter/blob/main/image/Screenshot%202026-04-28%20220607.png)
![Path Page](https://github.com/abyshk-np/Django-q-search-filter/blob/main/image/Screenshot%202026-04-28%20224009.png)
![Path Page](https://github.com/abyshk-np/Django-q-search-filter/blob/main/image/Screenshot%202026-04-28%20224047.png)
![Path Page](https://github.com/abyshk-np/Django-q-search-filter/blob/main/image/Screenshot%202026-04-28%20224106.png)

