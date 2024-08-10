# Antava: Office Automation System for Pediatric Doctor’s Office

## Project Overview
**Antava** is an office automation system designed specifically for pediatric doctor's offices. It aims to streamline operations, like inputting patient vitals or examination results, by reducing paperwork and enhancing the accessibility of patient records. The system is intended for use by doctors, nurses, patients, and their parents/guardians. This particular project focuses on a desktop application with a graphical user interface (GUI) built using Java and JavaFX.

## Features
### 1. Account Portal
- **Account Creation**: Patients can create accounts using a unique username.
- **Account Login**: 
  - **Patients**: Access their portal using a unique username and password.
  - **Nurses and Doctors**: Predefined login credentials to access their respective portals:
    - **Nurse Login**: Username: `nurse`, Password: `nurse321`
    - **Doctor Login**: Username: `doctor`, Password: `doctor321`
- **Role-Based Access**: The system restricts access based on the user's role, ensuring that nurses, doctors, and patients only see the information and features relevant to them.

### 2. Nurse Portal
- **Vitals Recording**: Nurses can record patient vitals (weight, height, body temperature, and blood pressure for patients over 12).
- **Health History Access**: Nurses can access a patient's medical history, including previous health issues, prescribed medications, and immunization records.
- **Health Questionnaire**: Nurses can ask health-related questions and record the responses in the system before the doctor’s examination.
- **Messaging System**: Nurses can send messages and reply to patients.

### 3. Doctor Portal
- **Patient Examination**: Doctors can record their findings during the physical examination.
- **Prescription Management**: Doctors can prescribe medications and send prescriptions directly to the patient's preferred pharmacy.
- **Medical History Review**: Doctors have access to the patient’s full medical history, including past visits, medications, and immunizations.
- **Messaging System**: Doctors can send messages and reply to patients.

### 4. Patient Portal
- **Account Management**: Patients can manage their accounts, which are uniquely identified by their first name, last name, and date of birth.
- **Contact Information**: Patients can view and update their contact information.
- **Patient Medical Records**: Stores and manages a patient's medical records including immunization history, current prescriptions, and any previous health issues.
- **Visit Summaries**: Patients can access summaries of their previous visits.
- **Messaging System**: Patients can send messages to doctors or nurses and receive responses via the system.


## System Operation

Upon arrival, the patient meets with a nurse who records vitals and any relevant health information. This data is entered into the system and made accessible to the attending doctor. The doctor then examines the patient, records any findings, prescribes medications if necessary, and provides additional recommendations. All interactions and data are stored within the system for future reference.

Patients can interact with the system via a portal, allowing them to view their medical history, update personal information, and communicate with their healthcare providers.

## Installation & Setup

1. **Prerequisites**:
   - Java Development Kit (JDK) 8 or later
   - JavaFX SDK
   - Integrated Development Environment (IDE) such as IntelliJ IDEA or Eclipse

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/antava.git
   ```
   
3. **Build the Project**:
   - Open the project in your IDE
   - Ensure that JavaFX is properly configured in your build settings.
   - Compile and run the application.

## Acknowledgments
This project was developed by a [team of students](https://github.com/cse360antava/Group-Project) from the Arizona State University (ASU) CSE 360 course. Our collaborative effort focused on designing and implementing Antava as a simulation of an office automation system for a pediatric doctor's office. This project serves as a practical demonstration of our understanding and skills acquired throughout the course.


