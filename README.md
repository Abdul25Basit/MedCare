# MedCare

MedCare is a healthcare application that makes online medical services seamless, accurate, fast, and reliable. It aims to create an ecosystem that makes healthcare accessible to everyone. Using intelligent technology, our application provides cutting-edge healthcare systems.

## Table of Contents

- [Features](#features)
- [Architecture](#architecture)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)

## Features

- **Healthcare Appointments**: Bridges the communication gap between healthcare providers and patients with a smart appointment reminder system on WhatsApp.
- **Digital Prescription**: Access digital prescriptions directly through WhatsApp, eliminating the hassle of deciphering handwritten notes.
- **Symptom Checker**: A machine learning-based tool that provides a prognosis of the disease based on symptoms experienced by the patient, along with precautions and medications.
- **Health-Insurance Charges Prediction**: Predicts applicable insurance charges based on health information provided by the user.
- **Diet Recommendation System**: Offers customized nutritional recommendations for users' well-being.

## Architecture

MedCare is built using a modern web architecture with the following components:

- **Frontend**: Built with React.js for a dynamic user experience.
- **Backend**: Developed using Django to handle user data and application logic.
- **Database**: Utilizes a relational database for storing user data, medical records, and prescriptions.
- **Third-Party Integration**: Leverages Twilio for communication and notifications.

## Tech Stack

- **Frontend**:
  - React.js
  - Tailwind CSS for styling

- **Backend**:
  - Django
  - Python

- **Database**:
  - PostgreSQL or SQLite

- **Third-Party Services**:
  - Twilio for WhatsApp notifications

## Installation

### Prerequisites

- Python 3.x
- Django
- PostgreSQL or SQLite
- Twilio account

### Clone the Repository

```bash
git clone https://github.com/Abdul25Basit/MedCare.git
cd MedCare
Backend Setup
Navigate to the backend directory (if applicable):

bash
Copy code
cd backend  # Adjust this path as needed
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run migrations (if using a database):

bash
Copy code
python manage.py migrate
Start the backend server:

bash
Copy code
python manage.py runserver
Frontend Setup
Navigate to the frontend directory (if applicable):

bash
Copy code
cd frontend  # Adjust this path as needed
Install Node.js dependencies:

bash
Copy code
npm install
Start the React development server:

bash
Copy code
npm start
Usage
Starting the Application
Ensure that the database is running (if applicable).
Start the backend server.
Launch the frontend React app.
Accessing the Application
Frontend: http://localhost:3000
Backend API: http://localhost:8000
Screenshots
Here are some screenshots of the application:

Home Page:


Appointment Page:

Symptom Checker:

Diet Recommendations:

Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes.
Submit a pull request with a clear description of your changes.
