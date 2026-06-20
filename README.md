# tendercare-healthcare-system
# Tender Care Healthcare Management System

## Project Overview

Tender Care Healthcare Management System is a backend-driven healthcare application developed using Python, Django, and PostgreSQL. The system assists healthcare facilities in managing patient records, appointments, medical records, and email notifications.

The system supports both new and returning patients, allowing healthcare providers to retrieve patient history, manage consultations, and maintain accurate medical records.

---

## Problem Statement

Many small clinics and healthcare facilities struggle with managing patient records manually. This leads to lost records, duplicate patient registrations, scheduling conflicts, and difficulty tracking patient history.

Tender Care Healthcare Management System provides a centralized solution for managing patient information, appointments, and medical records efficiently.

---

## Objectives

### Main Objective

To develop a healthcare management system that streamlines patient registration, appointment scheduling, medical record management, and communication through email notifications.

### Specific Objectives

* Register and manage new patients.
* Retrieve information for returning patients.
* Manage doctor records.
* Schedule appointments.
* Maintain patient medical records.
* Send automated email notifications.
* Generate healthcare reports.

---

## Features

### Patient Management

* Register new patients.
* Generate unique Patient IDs.
* Update patient information.
* Search returning patients.
* Retrieve patient history.

### Doctor Management

* Add doctors.
* Update doctor details.
* Manage doctor specialization.

### Appointment Management

* Schedule appointments.
* View appointments.
* Update appointment status.
* Prevent duplicate appointments.

### Medical Records

* Record diagnoses.
* Record treatments.
* Record prescriptions.
* View patient visit history.

### Email Notifications

* Welcome email after registration.
* Appointment confirmation emails.
* Medical record update notifications.

### Reports

* Registered patients report.
* Appointment report.
* Doctor report.
* Medical records report.

---

## Technologies Used

* Python
* Django
* PostgreSQL
* HTML (Optional Admin Templates)
* Bootstrap (Optional)

---

## User Roles

### Administrator

* Manage users.
* Manage doctors.
* View reports.

### Receptionist

* Register patients.
* Search returning patients.
* Schedule appointments.

### Doctor

* View appointments.
* Update medical records.
* Record diagnoses and prescriptions.

---

## System Workflow

New Patient:

Register Patient → Generate Patient ID → Book Appointment → Consultation → Medical Record → Email Notification

Returning Patient:

Search Patient → Retrieve History → Book Appointment → Consultation → Update Medical Record → Email Notification



<img width="308" height="620" alt="image" src="https://github.com/user-attachments/assets/87d89a3c-8932-44fb-aff9-573e07e37f63" />


---

## Database Tables

1. Users
2. Patients
3. Doctors
4. Appointments
5. Medical Records
6. Email Logs

---

## Programming Concepts Demonstrated

* Variables and Data Types
* Control Structures
* Functions
* Lists and Dictionaries
* Classes and Objects
* Inheritance
* Encapsulation
* Exception Handling
* Database Connectivity
* Modular Programming

---

## Future Improvements

* SMS Notifications
* Online Patient Portal
* Payment Integration
* Laboratory Management
* Pharmacy Management
* AI-powered Health Insights

---

tender_care_system/
│
├── manage.py
│
├── tender_care_system/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── accounts/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── admin.py
│   └── services.py
│
├── patients/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── admin.py
│   └── services.py
│
├── doctors/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── admin.py
│   └── services.py
│
├── appointments/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── admin.py
│   └── services.py
│
├── records/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── admin.py
│   └── services.py
│
├── notifications/
│   ├── migrations/
│   ├── models.py
│   ├── email_service.py
│   ├── services.py
│   └── templates/
│       └── emails/
│           ├── welcome_email.html
│           ├── appointment_confirmation.html
│           └── medical_record_update.html
│
├── reports/
│   ├── report_service.py
│   └── analytics.py
│
├── utils/
│   ├── validators.py
│   ├── exceptions.py
│   └── helpers.py
│
├── templates/
├── static/
├── media/
│
├── requirements.txt
├── README.md
└── .env

Core Database Relationships
Patient
   │
   ├── Appointments
   │
   ├── Medical Records
   │
   └── Email Logs

Doctor
   │
   ├── Appointments
   │
   └── Medical Records

## Author

Asasira Queen Pinklen



Final Year Software Engineering Project
Tender Care Healthcare Management System
