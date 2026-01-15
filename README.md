# DevSearch

> [!NOTE] > **This project is currently ongoing.** I am actively working on it and adding new features.

DevSearch is a social network for developers to showcase their projects and connect with others. This project is built using Django.

## Features

- **Project Management**: Users can create, view, and manage their development projects.
- **Developer Profiles**: Showcases developers and their expertise.
- **Connection**: Networking platform specifically for the developer community.

## Tech Stack

- **Backend**: Django 6.0.1
- **Database**: SQLite3
- **Language**: Python

## Getting Started

### Prerequisites

- Python 3.x
- Django

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Sosthenes-arch/devsearch.git
   cd devsearch
   ```

2. (Optional) Create a virtual environment:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. Install dependencies:

   ```bash
   pip install django
   ```

4. Run migrations:

   ```bash
   python manage.py migrate
   ```

5. Start the development server:

   ```bash
   python manage.py runserver
   ```

6. Open your browser and navigate to `http://127.0.0.1:8000/`.

## License

This project is open-source.
