Travel Packages Full Stack Application
This is a full-stack web application for managing travel packages, built with:

Backend: Spring Boot (Java)

Frontend: React.js

Project Structure
bash
Copy
Edit
TravelPackagesFullStackSpringBoot/
├── travelpackages/          # Spring Boot backend
├── travel-agency/         # React frontend
└── README.md         # This file
Running the Project
Backend (Spring Boot)
Navigate to the backend directory:

bash
Copy
Edit
cd backend
Run the Spring Boot application:

bash
Copy
Edit
./mvnw spring-boot:run  # or use your IDE to run the main class
The backend server will start on http://localhost:8080.

Frontend (React)
Navigate to the frontend directory:

bash
Copy
Edit
cd frontend
Install dependencies (if you haven’t already):

nginx
Copy
Edit
npm install
Start the React development server:

sql
Copy
Edit
npm start
The frontend will open on http://localhost:3000.

Building for Production
In the frontend folder, build the React app:

arduino
Copy
Edit
npm run build
Copy the contents of frontend/build into backend/src/main/resources/static so Spring Boot serves the frontend.

Author
Rishitha U M
