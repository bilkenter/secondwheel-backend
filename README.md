### SECONDWHEEL
Second-Hand Vehicle Buying and Selling Platrform

## Backend Setup

1. **Create and activate a virtual environment:**

   ```
   # Create virtual environment
   py -m venv envName
   # Activate virtual environment (Windows)
   envName\Scripts\activate.bat
   ```

2. **Navigate to the backend directory:**

   ```
   cd path/to/api
   ```

3. **Install Python requirements:**
   ```
   pip install -r requirements.txt
   ```

## Database Setup

4. **Prepare and apply migrations:**

   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Run the backend server:**
   ```
   python manage.py runserver
   ```
