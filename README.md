# **Hello World Django App**

This is a basic Django web application that responds with a JSON object containing the message `"Hello World!"`. 

## **Features**
- A single route (`/hello/`) that returns:
  ```json
  {
    "Message": "Hello World!"
  }
  ```
- Built using Django.

---

## **Requirements**
- Python 3.x
- Django (latest version)
- Git (for version control)

---

## **Installation Instructions**

1. **Clone the Repository**  
   Clone this project to your local machine:
   ```bash
   git clone <your-repo-url>
   cd hello_world_project
   ```

2. **Create and Activate a Virtual Environment**  
   ```bash
   python -m venv venv
   source venv/bin/activate   # For Linux/Mac
   venv\Scripts\activate      # For Windows
   ```

3. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Database Migrations**  
   ```bash
   python manage.py migrate
   ```

5. **Start the Development Server**  
   ```bash
   python manage.py runserver
   ```

---

## **Usage**
1. Open your browser and navigate to:  
   ```
   http://127.0.0.1:8000/hello/
   ```
2. You should see the following JSON response:
   ```json
   {
     "Message": "Hello World!"
   }
   ```

---

