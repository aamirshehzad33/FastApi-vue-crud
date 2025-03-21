
# FastAPI + Vue.js CRUD 

## Overview
This project is a full-stack CRUD (Create, Read, Update, Delete) application built using **FastAPI** for the backend and **Vue.js** for the frontend. It provides a seamless and efficient way to manage data with a responsive and interactive user interface.

## Tech Stack
### Backend (FastAPI)
- **FastAPI**: High-performance web framework for APIs with automatic OpenAPI and documentation support.
- **SQLAlchemy**: ORM for database interactions.
- **Alembic**: Database migration tool for handling schema changes.
- **SQLite/PostgreSQL/MySQL**: Choice of database for data persistence.
- **Pydantic**: Data validation and serialization.
- **Uvicorn**: ASGI server for running the FastAPI application.

### Frontend (Vue.js)
- **Vue.js**: Progressive JavaScript framework for building user interfaces.
- **Vue Router**: For handling navigation and routes.
- **Vuex / Pinia**: State management solution.
- **Axios**: HTTP client for API requests.
- **Bootstrap / Tailwind CSS**: Styling and UI components.

## Features
- 🔹 Full CRUD operations: Create, Read, Update, Delete.
- 🔹 FastAPI backend with automatic API documentation.
- 🔹 Vue.js frontend with dynamic UI and state management.
- 🔹 Secure authentication (JWT-based login system).
- 🔹 Database integration with SQLAlchemy and Alembic for migrations.
- 🔹 Responsive design for all devices.

## Installation Guide
### Backend Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/FastApi-vue-crud.git
   cd FastApi-vue-crud
   ```
2. **Create a virtual environment and activate it**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
4. **Run database migrations with Alembic**
   ```sh
   alembic upgrade head
   ```
5. **Run the FastAPI server**
   ```sh
   uvicorn main:app --reload
   ```
6. **Access API docs**
   - Open `http://127.0.0.1:8000/docs` for Swagger UI.

### Frontend Setup
1. **Navigate to the frontend directory**
   ```sh
   cd frontend
   ```
2. **Install dependencies**
   ```sh
   npm install
   ```
3. **Run the Vue.js development server**
   ```sh
   npm run dev
   ```
4. **Access the frontend**
   - Open `http://localhost:5173` in your browser.

## API Endpoints
| Method | Endpoint      | Description           |
|--------|--------------|-----------------------|
| GET    | /items       | Fetch all items      |
| POST   | /items       | Create a new item    |
| GET    | /items/{id}  | Get a specific item  |
| PUT    | /items/{id}  | Update an item       |
| DELETE | /items/{id}  | Delete an item       |

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## License
This project is licensed under the MIT License.

---
🚀 **Happy Coding!** 🎉

