
## Hello World Django App

### Project Overview
This project is a simple Django application that responds with a JSON message `{"Message": "Hello World!"}` at a specified endpoint.

### Prerequisites
Ensure you have the following installed on your machine:
- **Python 3.x**
- **pip** (Python package manager)
- **Django** (installed via pip)

### Steps to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Manoj-Ashokreddy/Lab_5_Build-Hello-World-Django-App.git
   cd Lab_5_Build-Hello-World-Django-App
   ```
2. **Set up a Virtual Environment**:
  
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
   
3. **Install Django**:
   If Django is not installed, run:
   ```bash
   pip install django
   ```

4. **Run the Django Development Server**:
   Start the Django development server:
   ```bash
   python manage.py runserver
   ```

5. **Access the Hello World Endpoint**:
   - Open a browser and visit:  
     `http://localhost:8000/hello/`
   - The browser should display the following JSON response:
     ```json
     {"Message": "Hello World!"}
     ```
