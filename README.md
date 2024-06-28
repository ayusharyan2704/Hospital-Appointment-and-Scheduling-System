# Hospital Appointment and Scheduling System

## Overview

The Hospital Appointment and Scheduling System is designed to streamline the appointment booking process for patients and improve scheduling efficiency for doctors and administrative staff.

## Features

- **Patient Interface:**
  - Register/Login: Patients can create accounts or log in using existing credentials.
  - Appointment Booking: Patients can view available time slots and book appointments with preferred doctors.
  - Appointment Management: View, reschedule, or cancel appointments as needed.

- **Doctor Interface:**
  - Dashboard: Doctors can manage their availability and view upcoming appointments.
  - Appointment Management: Doctors can accept, reject, or reschedule appointments based on availability.

- **Admin Interface:**
  - User Management: Admins can manage patient and doctor accounts.
  - Appointment Management: Admins can oversee and modify appointments for both patients and doctors.

- **Notification System:**
  - Email notifications for appointment confirmation, reminders, and cancellations.

## Installation

To run the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ayusharyan2704/Hospital-Appointment-and-Scheduling-System.git
   cd Hospital-Appointment-and-Scheduling-System
2. **Install Dependencies:**
   ```bash
      npm install
3. Set up the database:
     Create a MongoDB database and configure the connection string in config.js.
4. Start the server:  node server.js

## Usage

  Patient Interface:
        Register or log in with existing credentials.
        Book, reschedule, or cancel appointments.

  Doctor Interface:
        Log in and manage availability.
        Accept, reject, or reschedule appointments.

  Admin Interface:
        Log in and manage user accounts and appointments.
