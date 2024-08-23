Here's an updated README based on your setup instructions:

---

# Setting Up the Application

After downloading/cloning the repository, follow these steps to set up the project:

1. **Backend Setup:**

   - Open a terminal and navigate to the `backend` directory:
     ```bash
     cd backend
     ```
   - Create and activate a Python virtual environment:
     ```bash
     python -m venv env
     ./env/Scripts/activate
     ```
   - Install the required Python packages:
     ```bash
     pip install -r requirements.txt
     ```
   - Run database migrations:
     ```bash
     python manage.py migrate
     ```
   - Start the Django development server:
     ```bash
     python manage.py runserver
     ```

2. **Frontend Setup:**

   - Open a second terminal and navigate to the `frontend` directory:
     ```bash
     cd frontend
     ```
   - Install the necessary Node.js packages:
     ```bash
     npm install
     ```
   - Start the frontend development server:

     ```bash
     npm run server
     ```

   - Open the URL provided by the frontend server in your browser.

## All set! Happy coding :)

---
