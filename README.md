
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
   ```

2. **Install Django**:
   If Django is not installed, run:
   ```bash
   pip install django
   ```

3. **Run the Django Development Server**:
   Start the Django development server:
   ```bash
   python manage.py runserver
   ```

4. **Access the Hello World Endpoint**:
   - Open a browser and visit:  
     `http://localhost:8000/hello/`
   - The browser should display the following JSON response:
     ```json
     {"Message": "Hello World!"}
     ```

### Project Structure

```
helloworld_project/
│
├── helloworld_app/
│   ├── migrations/
│   ├── views.py                # Contains the view that returns the Hello World JSON message
├── manage.py                   # Django project management script
├── helloworld_project/
│   ├── settings.py             # Project settings
│   ├── urls.py                 # URL routing for the project
```

### How to Access the Hello World JSON Response
Visit the following URL after running the development server:
- `http://localhost:8000/hello/`

```
