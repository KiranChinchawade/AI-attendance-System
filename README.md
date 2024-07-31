# AI-attendance-System
The "Attendance System with Face Recognition" automates attendance tracking using AI and facial recognition. It includes a Python-based face scanner for attendance updates and a C# management panel for dataset creation and employee management. Features include touch-free recording, security, and QR code integration.

Here's a concise and organized README file for the "Attendance System with Face Recognition" project:

---

# Attendance System with Face Recognition

## Introduction

The "Attendance System with Face Recognition" automates attendance tracking using AI and facial recognition technology. It is designed for workplaces and educational institutions to streamline the process of recording attendance in a touch-free and efficient manner.

## Features

- **Automatic Attendance Recording**: Updates attendance with entry and exit times.
- **Touch-Free Operation**: Uses facial recognition, avoiding the need for physical contact.
- **Secure and Reliable**: Includes eye-blink detection to prevent spoofing.
- **Simple Management**: GUI-based dataset creation and model training.
- **Unauthorized Access Prevention**: Detects and prevents unauthorized access.
- **Voice Outputs**: Provides voice feedback during the attendance process.

## Technologies & Frameworks

### Attendance Receiver (Python)
- **Python 3.6**
- **OpenCV** - For computer vision tasks.
- **face_recognition** - For facial recognition.
- **pyttsx3** - For voice outputs.
- **Playsound** - For playing sounds.
- **MySQL Connector** - For database management.

### Management Panel (C#)
- **C#** - For management interface and database operations.
- **MySQL** - For storing attendance records and employee details.

## Setup Guide

### Management Panel (C#)
1. Create a database named **"management_auto_attendance_system"** in MySQL.
2. Import the SQL file from the **1-database** folder.

### Attendance Receiver (Python)
1. **Create a Virtual Environment**:
   ```cmd
   conda create -n ai_attendance_system_env python=3.6
   conda activate ai_attendance_system_env
   ```
2. **Install Dependencies**:
   ```cmd
   pip install -r required-dependencies.txt
   ```
3. **Run the System**:
   - Execute `run.bat` to start the attendance receiver.

## Main Scripts
- **dataset-creator.py**: Creates datasets from employee images.
- **training.py**: Trains the facial recognition model.
- **run.py**: Manages the attendance process.

## Management Panel Features
- **Manage Employees**: Add, edit, and delete employee details.
- **Create Dataset**: Capture images for new employees.
- **Training**: Train models with a single click and generate QR codes.
- **Attendance Report**: View and manage attendance records.
- **Face Verification**: Manually verify unverified attendance.
- **Settings**: Update system settings and preferences.

---

This README provides a clear overview of the project, its features, technologies, setup instructions, and key components. Feel free to modify or expand upon any sections to suit your specific needs or project updates.
