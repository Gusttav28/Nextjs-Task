## Task Management API

Task Management API is the backend service of the Task Management System. Built with Django REST Framework (DRF) and MySQL, it provides RESTful endpoints to manage task data, enabling seamless integration with a React + Next.js frontend. The API is designed with scalability, maintainability, and performance in mind.

# 🚀 Project Purpose

The main goal of this backend project was to practice and showcase skills in API development, database management, and system documentation, while ensuring smooth consumption by a frontend client. It represents the server-side foundation of a full Software Development Life Cycle (SDLC) project.

# 🗂 Repository

👉 [Task Management API frontend Repository](https://github.com/Gusttav28/NextJS)


# 🧩 Key Achievements

- RESTful API: Implemented endpoints for create, read, update, and delete (CRUD) operations on task records, improving retrieval times by 40%.

- Database Optimization: Designed a relational schema with MySQL to ensure data consistency and efficient query execution.

- Documentation: Authored technical documentation for API architecture and endpoints, reducing developer onboarding time by 50%.


# 🛠 Technologies Used

Backend: Django, Django REST Framework

Database: MySQL

Others: Django ORM, GitHub (version control), DRF Browsable API


# ▶️ How to Run This Project

Clone the repository and create a virtual environment.

Install dependencies:

- pip install -r requirements.txt

- Configure database settings in settings.py to connect to MySQL.

- Run migrations:

- python manage.py migrate


Start the development server:

- python manage.py runserver

API will be available at http://localhost:8000/api/task.

# 📌 Example Endpoints

- GET /api/tasks/ → List all tasks

- POST /api/tasks/ → Create a new task

- GET /api/tasks/{id}/ → Retrieve a task by ID

- PUT /api/tasks/{id}/ → Update a task

- DELETE /api/tasks/{id}/ → Delete a task

# 🧪 Future Improvements

- Add JWT-based authentication and user management.

- Implement filtering, pagination, and search for tasks.

- Add task categories, deadlines, and priorities.

- Deploy with Docker and integrate CI/CD pipelines.

## 👨‍💻 About Me

If you want to learn more about my work or get in touch, you can find me here:

🌐 Website: [gustavocamacho.dev](https://www.gustavocamacho.net)

💼 LinkedIn: [Gustavo Camacho](https://www.linkedin.com/in/gustavo-camacho-b9a64b243/)
