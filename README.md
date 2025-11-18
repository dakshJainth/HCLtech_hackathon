# HCLtech_hackathon
A full-stack web application built for the HCLTech  This Minimum Viable Product (MVP) provides a secure, role-based portal for patients to track wellness goals and for healthcare providers to monitor patient compliance.

Table of Contents
-    Key Features
-   Tech Stack
-   Architecture Overview
-    Getting Started
    -   Prerequisites
    -   Backend Setup
    -   Frontend Setup
-   Environment Variables
-   API Endpoints
-   Deployment 

Patient Dashboard
 A clear overview of daily goals, reminders, and health tips.
  
  1 Login & Public Page
 
  2.Secure login and a public-facing page with general health information.



Key Features
For Patients:
-   Profile Management: View and edit personal deatails and health issuses.
-   Personalized Dashboard: A view of wellness ,goal ,progress (steps, sleep, water intake).
-   Goal Tracking: Simple interface to log daily wellness activities.
-   Basic  Health Tip of the Day:Receive a simple, actionable health tip daily.

For Healthcare Providers:
  Secure Login: Separate and secure access for healthcare professionals.
  Patient View: View a list of assigned patients and their health issues. 
  Patient List:Easily navigate to see more detailed goal and compliance data for each patient.

General & Security:
-   Secure Authentication System:login using JWT (JSON Web Tokens) with appropriate expiration.
-   Password Security: All user passwords are securely hashed using bcrypt  js.
Consent & Privacy: A consent checkbox is implemented during registration, and a static privacy policy page is available.
RESTful API: A clean, well-structured API serves as the backbone for communication between the frontend and backend.




Tech Stack


 Frontend
     Reactjs,tailwind ,html, css and js

Backend
     Nodejs, express js 

Database
      Mongo db

Authentication 
   Json web Tokens, bycrpt.js

Deployment
   Vercel(frontend),render(backend),mogodb atlas(database)



 








