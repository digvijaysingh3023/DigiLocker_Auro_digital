# DigiLocker Clone

DigiLocker Clone is a web application that allows users to securely upload, view, share, and verify documents. It incorporates user authentication and provides a user-friendly interface for managing personal documents.

## Features
- **User Authentication**: SignUp, Login, and Logout functionality for secure access.
- **Document Management**: 
  - Upload documents.
  - View and verify uploaded documents.
  - Generate QR codes for sharing documents.
  - Open documents in a new tab for viewing without downloading.
- **Responsive Design**: Optimized for desktop and mobile devices.

## Technologies Used
- **Backend**: Django, Django REST Framework
- **Frontend**: HTML, CSS, Bootstrap, JavaScript
- **Database**: SQLite (default for Django projects)
- **Others**: QR Code generation using `qrcode.js`

## Installation and Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/digvijaysingh3023/DigiLocker_Auro_digital.git
2. **Set up a virtual environment**:
    ```bash
    python3 -m venv env
    source env/bin/activate  # For Linux/Mac
    env/Scripts/activate     # For Windows
3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
4.  **Apply migrations**:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
5.  **Run the development server**:
    ```bash
    python manage.py runserver
6.  **Open your browser and navigate to http://127.0.0.1:8000/**.

## Usage
1. **Sign Up and Login**
    - Navigate to /signup/ to create an account.
    Use /login/ to access your account.

2. **Document Upload**

    - Go to the Upload Document page.
    - Enter a title and choose a file to upload.

3. **View Documents**

    - Access the View Documents page to see a list of uploaded documents.

    - Use the View button to open a document in a new tab.

    - Use the Verify button to mark a document as verified.

    - Use the Share button to generate a QR code for sharing the document link.

4. **Logout**
    - Use the Logout button to end the session securely.

## License
**This project is licensed under the MIT License. See the LICENSE file for more details.**