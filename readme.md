Credit Card Information Access System
This project is a Python application that implements a Credit Card Information Access System using face recognition. Users can register their credit card information along with their face, and later access their credit card information by verifying their face.

Features
User Registration: Users can register their credit card information along with their face by providing their name, credit card number, and capturing their face.
Face Recognition: Registered users can access their credit card information by verifying their face through face recognition.
Fraud Detection: The system detects fraud when an unregistered user tries to access credit card information using a previously registered credit card.


cd credit-card-system
Install dependencies:
pip install -r requirements.txt
pip install git+https://github.com/ageitgey/face_recognition_models

Run the application:

streamlit run main.py
Access the application in your web browser at the provided URL.

Use the sidebar to register new users by providing their name, credit card number, and capturing their face.

Registered users can access their credit card information by entering their credit card number and verifying their face.

File Structure
user_database.xlsx: Excel file to store registered user data.
requirements.txt: File containing a list of Python dependencies for the project.
app.py: Main Python script containing the Streamlit UI and functionality.
.streamlit/config.toml: Configuration file for Streamlit.