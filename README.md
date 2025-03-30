MYCLICKDOCTOR is an online platform that enables patients to consult with doctors remotely via video calls. The application facilitates seamless communication between healthcare providers and patients, ensuring convenient and efficient medical consultations.
Features
•	Doctor & Patient Registration – Users can sign up as doctors or patients.
•	Appointment Scheduling – Patients can book appointments with available doctors.
•	Secure Video Consultations – Powered by Jitsi for real-time video calls.
•	Chat & Messaging – Secure communication between doctors and patients using SignalR.
•	Medical Records Management – Patients can upload and store their medical history.
•	Payment Integration – Barion payment gateway for secure online transactions.
Tech Stack
•	Frontend: Angular (MUI Tools, TypeScript)
•	Backend: .NET Core
•	Database: SQL Server
•	Video Call: Jitsi
•	Chat: SignalR
•	Storage: AWS S3 (for storing files and medical records)
•	Task Management: Celery (for background tasks like document conversion using LibreOffice)
•	Payment Gateway: Barion
Installation
Prerequisites
•	.NET Core installed
•	Node.js and npm installed
•	AWS S3 configured for file storage
•	Jitsi configured for video calls
•	SignalR configured for real-time chat
•	Barion payment gateway setup
•	Celery and Redis configured for task management




Setup
Backend
cd backend
# Install dependencies
dotnet restore
# Run the application
dotnet run
Frontend
cd frontend
# Install dependencies
npm install
# Start the frontend
ng serve
Configuration
•	Jitsi: Set up a Jitsi server or use the Jitsi Meet API.
•	AWS S3: Configure storage credentials for file uploads.
•	LibreOffice & Celery: Ensure LibreOffice is installed and Celery workers are running for document processing.
•	SignalR: Set up SignalR for real-time chat between users.
•	Barion: Configure Barion API keys for payment processing.
Contributing
Contributions are welcome! Please follow these steps:
1.	Fork the repository.
2.	Create a new branch.
3.	Make your changes and commit them.
4.	Push to your fork and submit a pull request.
License
This project is licensed under the MIT License.
Contact
For any inquiries, please contact .
________________________________________
Note: This project is running in Hungary.






# Myclickdoctor

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


<!-- The core Firebase JS SDK is always required and must be listed first -->
<!-- <script src="https://www.gstatic.com/firebasejs/8.1.1/firebase-app.js"></script> -->

<!-- TODO: Add SDKs for Firebase products that you want to use
     https://firebase.google.com/docs/web/setup#available-libraries -->
<!-- <script src="https://www.gstatic.com/firebasejs/8.1.1/firebase-analytics.js"></script> -->

<!-- <script> -->
  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  // var firebaseConfig = {
  //   apiKey: "IIIIIIIIII-1wMIL9a8dA4Ytw",
  //   authDomain: "myclickdoctor.JN.com",
  //   databaseURL: "https://KKLNL.N.com",
  //   projectId: "NJBJB",
  //   storageBucket: "myclickdoctor.JKNJKNJK.com",
  //   messagingSenderId: "442620068561",
  //   appId: "1:442620068561:web: BJBJBBK",
  //   measurementId: "G-NJKNJK"
  // };
  // Initialize Firebase
  // firebase.initializeApp(firebaseConfig);
  // firebase.analytics();
<!-- </script> -->
