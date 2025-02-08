# Movie--Review-API

#  Movie Review API with React Frontend


![Capture](https://github.com/user-attachments/assets/7ab41a3a-a6e4-49ce-b720-5d57c5806c2d)
![Capture1](https://github.com/user-attachments/assets/40b10f4a-805a-4067-8245-f13b2b504d42)
![Capture2](https://github.com/user-attachments/assets/9a673103-8997-4cc6-b446-1a5c2f2c6401)
![Capture3](https://github.com/user-attachments/assets/9fc087ca-9f29-4dee-9bb4-825a4e9f89ea)
![Capture4](https://github.com/user-attachments/assets/0b0ae1df-95c6-41a4-8201-d38205d1e293)
![Capture5](https://github.com/user-attachments/assets/662ed9ed-cfbd-4bf4-ac95-9a3b49ce0f58)
![Capture6](https://github.com/user-attachments/assets/57c43eeb-3321-42c7-9505-e831bc00b281)

This project is a **Movie Review API** built using **Django Ninja** for the backend and a **React** frontend. It allows users to view and review movies with details like director and rating.

##  Features
-  Add, update, and delete movie reviews
-  View movie details including title, director, and rating
-  Fast and lightweight API using Django Ninja
-  Interactive and visually appealing React frontend

##  Project Structure
```
movie-review-api-react/
├── backend/   # Django Ninja API
├── frontend/  # React Frontend
└── README.md
```

---

##  Installation & Setup

###  Backend Setup (Django Ninja)
1. Navigate to the `backend/` directory:
   ```sh
   cd backend
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Apply database migrations:
   ```sh
   python manage.py migrate
   ```
5. Start the Django server:
   ```sh
   python manage.py runserver
   ```

The backend will run at `http://127.0.0.1:8000/`.

---

### 3 Frontend Setup (React)
1. Navigate to the `frontend/` directory:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React development server:
   ```sh
   npm start
   ```

The frontend will run at `http://localhost:3000/`.

---

##  API Endpoints
| Method | Endpoint | Description |
|--------|----------------------|--------------------------------|
| GET    | `/movies/`           | Fetch all movies |
| GET    | `/movies/{id}/`      | Fetch details of a single movie |
| POST   | `/movies/`           | Add a new movie |
| PUT    | `/movies/{id}/`      | Update a movie |
| DELETE | `/movies/{id}/`      | Delete a movie |

---

##  Technologies Used
- **Backend:** Django, Django Ninja, SQLite
- **Frontend:** React, CSS, JavaScript
- **Tools:** Git, VS Code, Postman

---

##  Contributing
Feel free to fork this repository and contribute to its development.

---

## 🌟 Show Your Support
Give a ⭐ if you like this project!
