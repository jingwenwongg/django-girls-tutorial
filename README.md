# Django Girls Blog

A simple blog application built by following the [Django Girls Tutorial](https://tutorial.djangogirls.org/).

## Tech Stack
* Python
* Django
* HTML/CSS
* Bootstrap

## Features
* **Create, edit, and delete** blog posts directly from the site.
* **Admin dashboard** to manage all content.
* **Responsive design** using Bootstrap.
* Live deployment on **PythonAnywhere**.

## Run Locally

1. Clone the repository

```bash
git clone <repository-url>
cd <repository-name>
```

2. Create and activate a virtual environment

```bash
python -m venv venv
```

Mac/Linux:

```bash
source venv/bin/activate
```

Windows:

```bash
venv\Scripts\activate
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Apply database migrations

```bash
python manage.py migrate
```

5. Run the development server

```bash
python manage.py runserver
```

6. Open in browser:

```text
http://127.0.0.1:8000
```
