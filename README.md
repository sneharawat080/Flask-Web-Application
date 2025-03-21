# Flask To-Do App

## Description
A simple to-do list web application built using Flask and SQLite. Users can add and delete tasks with ease.

## Features
- Add tasks
- Delete tasks
- View all tasks
- Lightweight and easy to use

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/flask-todo-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd flask-todo-app
   ```
3. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the application:
   ```sh
   python app.py
   ```
2. Open your browser and go to `http://127.0.0.1:5000/`

## Deployment
To deploy on Heroku:
1. Install Heroku CLI and log in:
   ```sh
   heroku login
   ```
2. Create a Heroku app:
   ```sh
   heroku create flask-todo-app
   ```
3. Deploy the app:
   ```sh
   git add .
   git commit -m "Initial commit"
   git push heroku main
   ```

## License
This project is licensed under the MIT License.
