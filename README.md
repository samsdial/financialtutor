# FinancialTutor

FinancialTutor is a web application designed to help users manage their finances. The project is built using Django as the backend framework, HTMX for handling interactive elements, and SQLite as the database.

## Features

- **User Management**: Admin interface for managing users.
- **Finance Tracking**: Track and manage personal finance data.
- **Interactive UI**: HTMX is used to add interactivity without full page reloads.
- **Django Admin**: Integrated with Django’s admin panel to manage models and data.

## Project Structure

```
financialtutor/
│
├── finance_project/          # Root Django project folder
│   └── settings.py           # Django settings
├── tracker/                  # Django app for finance tracking
│   ├── templates/            # HTML templates for the app
│   ├── admin.py              # Django admin configurations
│   ├── models.py             # Database models for finance data
│   ├── views.py              # Views handling app logic
│   ├── urls.py               # URL routing for the app
│   └── migrations/           # Database migrations
├── manage.py                 # Django command-line utility
└── requirements.txt          # Python dependencies
```

## Installation

### Prerequisites

Ensure you have Python 3.x installed on your machine.

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/financialtutor.git
   cd financialtutor
   ```

2. **Create a virtual environment** (optional but recommended):

   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install the required dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations** to set up the database:

   ```bash
   python manage.py migrate
   ```

5. **Run the development server**:

   ```bash
   python manage.py runserver
   ```

6. **Access the application**:

   Open your browser and go to `http://127.0.0.1:8000/`.

## Usage

- Navigate through the finance tracker to add or view your personal finance data.
- The admin interface is available at `http://127.0.0.1:8000/admin/`.

## Technologies Used

- **Django**: Backend web framework
- **HTMX**: Used for interactive elements without page reloads
- **SQLite**: Default database used in development
- **Python**: Core programming language

## Video Tutorial
[Youtube Video](https://www.youtube.com/watch?v=6OlILeP9GKg&list=PL-2EBeDYMIbSBjHGYJYl1WLUT-tbCLHOb&index=1)

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for suggestions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
