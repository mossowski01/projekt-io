# FinTech

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## About the Project
This repository contains a web application for managing household finances, developed as part of the **Software Engineering (Inżynieria Oprogramowania)** course. The application provides tools to track income, expenses and budgets with an intuitive user interface.

We discussed the essence of effective household budget management in the presentation below:
https://www.canva.com/design/DAGWojqZPlU/uImw6tviVSSqz25mzelNQQ/edit?fbclid=IwZXh0bgNhZW0CMTEAAR3RKWpAmck1GxrmXwBU2dN1x8gQc0L_w4A7djVPoTXI77ncwba4BhMVQyc_aem_p3-9pX77nEbpIoik7U3_fw

The backend is powered by **Flask**, the frontend utilizes **HTML**, **CSS** and **JavaScript**, while **SQLite** is used as the database for persistent data storage.

---

## Features
The application offers the following key functionalities:
- **Income and Expense Management**: Add, edit, and categorize transactions.
- **Budget Planning**: Set monthly budgets and track spending limits.
- **Data Visualization**: Charts and reports for financial analysis.
- **User Authentication**: Secure login system to protect user data.
- **Persistent Data Storage**: Data is saved and accessible across sessions using SQLite.

---

## Technologies Used
The project utilizes the following technologies:
- **Backend**: Python with Flask for developing a lightweight and scalable server-side application.
- **Frontend**:  HTML, CSS and JavaScript for creating the user interface, ensuring responsiveness and interactivity.
- **Database**: SQLite as a lightweight database for storing and managing data efficiently.
- **Libraries/Frameworks**:
  - Flask 3.0.3: Used for backend routing, handling requests and serving the application.
  - flask_sqlalchemy 3.1.1: An Object Relational Mapper (ORM) for integrating SQL databases with Flask applications.
  - flask_login 0.6.3: A library for managing user authentication and session handling in Flask applications.
  - flask_bcrypt 1.0.1: A library for securely hashing passwords using the bcrypt algorithm. 
  - flask_migrate 4.0.7: An extension for managing database migrations using Alembic. 
  - reportlab 4.2.5: A powerful library for creating PDF documents programmatically. 
  - Bootstrap 5.1.3: Implements a modern, responsive design and simplifies the styling of forms and components.
  - Chart.js 4.3.0: Enhances the frontend with dynamic data visualization capabilities.

## Installation
Follow these steps to set up and run the application locally:

### Prerequisites
- Python 3.x
- A virtual environment tool (e.g., `venv` or `virtualenv`)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/mossowski01/projekt-io.git
   cd projekt-io/Projekt
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Initialize the SQLite database (Optional):
   ```bash
   flask db init
   flask db migrate -m "Initial migration"
   flask db upgrade
   ```

5. Start the development server:
   ```bash
   python app.py
   ```

6. Open the application in your web browser:
   ```
   http://127.0.0.1:5000
   ```

---

## Usage
1. **Register and Log In**: Create a user account to access the application.
2. **Add Transactions**: Record income and expenses with appropriate categories.
3. **Set Budgets**: Define monthly budgets to monitor spending.
4. **Analyze Data**: View charts and reports for insights into financial habits.

---

## Folder Structure
```plaintext
Projekt/

├── instance/              # SQLite database file
├── migrations/            # Database migration files
├── static/                # Frontend static files (CSS, JavaScript)
├── templates/             # HTML templates for Flask
├── app.py/                 # Entry point to run the application

├── Documentation.pdf      # Project documentation
├── README.md              # README file for the repository
├── requirements.txt       # Python dependencies


```

---

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/new-feature
   ```
5. Open a Pull Request.

---

## License
This project is licensed under the Freeware License. It may not be sold or modified in any way, such as by adding your own advertisement inside. It can only be distributed in its original, unchanged form.

---

## Contact
For questions or suggestions, feel free to reach out:
- **GitHub Profile**: [mossowski01](https://github.com/mossowski01)

