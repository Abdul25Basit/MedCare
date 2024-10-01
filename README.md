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

# Clone the repository
git clone https://github.com/yourusername/MedCare.git
cd MedCare

# Backend Setup
cd backend  # Adjust this path as needed
pip install -r requirements.txt  # Install dependencies
python manage.py migrate  # Run migrations (if using a database)
python manage.py runserver &  # Start the backend server (use '&' to run in the background)

# Frontend Setup
cd ../frontend  # Adjust this path as needed
npm install  # Install Node.js dependencies
npm start  # Start the React development server

