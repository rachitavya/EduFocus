# EduHub

## Steps to use the website
1. Create a python virtual environment:
   ```
   python -m venv /path/to/new/virtual/environment
   ```
2. Install the dependencies in requirments.txt by followind command:
   ```
   pip install -r requirements.txt
   ```
3. Move to /backend/EduFocus folder
4. Create a .env file to set django environment and just paste following code in it:
   ```
   SECRET_KEY='abcdefghij'
   DEBUG=True
   ```
6. Run django server by:
   ```
   python manage.py runserver
   ```
Boom! You're good to go.
