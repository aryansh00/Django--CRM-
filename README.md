**Django CRM**

#### Description
"This is a Customer Relationship Management (CRM) application built with Django. It allows users to manage customer information, track interactions, and generate reports, streamlining customer relationships."

#### Features
- **User authentication:** Secure login and user management.
- **Customer management:** Add, edit, and delete customer profiles.
- **Interaction tracking:** Log and view customer interactions.
- **Reporting:** Generate reports on customer data and interactions.
- **Responsive design:** Optimized for various devices.

#### Installation
Instructions for setting up the project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/aryansh00/Django--CRM.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Django--CRM
   ```
3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
4. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
5. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
6. Apply database migrations:
   ```bash
   python manage.py migrate
   ```
7. Create a superuser (for admin access):
   ```bash
   python manage.py createsuperuser
   ```
8. Run the development server:
   ```bash
   python manage.py runserver
   ```

#### Usage
Instructions on how to use the CRM application:
1. Open the app in your web browser at `http://127.0.0.1:8000`.
2. Log in using the superuser credentials created earlier.
3. Manage customers, track interactions, and generate reports through the admin interface.

#### Technologies Used
- Django
- Python
- HTML/CSS
- JavaScript
- MySql
  

#### Environment Variables
If your app requires any environment variables, include instructions for setting them:
"Create a `.env` file in the root directory and add the following variables:"
```
SECRET_KEY='your_secret_key'
DEBUG=True
```
