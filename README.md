# favoratee Project

Welcome to the **favoratee** project! This Django application helps users find books, read them, and share them via email. Users can also filter books by author and categories. This README will guide you through the installation process and getting started with the project.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- **Python 3.x**
- **pip** (Python package installer)
- **Django** (the project will install this automatically)

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**

   Open your terminal and run the following command to clone the repository:

   ```bash
   git clone https://github.com/yourusername/favoratee.git
   cd favoratee
   ```

2. **Create a virtual environment:**

   It is recommended to create a virtual environment to manage your project dependencies. You can create one using `venv`:

   ```bash
   python -m venv venv
   ```

   Activate the virtual environment:

   - On **Windows**:

     ```bash
     venv\Scripts\activate
     ```

   - On **macOS/Linux**:

     ```bash
     source venv/bin/activate 
     ```
     or
     ```
     source venv/scripts/activate
     ```

3. **Install the required packages:**

   With the virtual environment activated, install the necessary packages using the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations:**

   After installing the packages, run the following command to apply database migrations:

   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional):**

   If you want to access the Django admin panel, create a superuser by running:

   ```bash
   python manage.py createsuperuser
   ```

   Follow the prompts to set up your admin account.

## Running the Project

To start the development server, run the following command:

```bash
python manage.py runserver
```

You can now access the application by navigating to `http://127.0.0.1:8000/` in your web browser.

## Usage

Once the application is running, you can:

- **Find books:** Use the search functionality to find books by title, author, or category.
- **Read books:** Click on a book to view its details and read it.
- **Share books:** Use the email feature to share book details with friends.
- **Filter books:** Use the filtering options to narrow down your search by author or category.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to report a bug, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for using favoratee! We hope you enjoy finding and sharing books with this application. If you have any questions or need further assistance, feel free to reach out. Happy reading!
```
