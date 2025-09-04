
Audio to Text Transcriber 🎧

A full-stack web application that transcribes audio files to text using a Spring Boot backend and a React frontend. The transcription is powered by OpenAI's Whisper API.

<img width="1024" height="450" alt="image" src="https://github.com/user-attachments/assets/26631982-c95e-4a61-a14b-aebbe6ce4ab5" />

Features: 
Simple File Upload: A clean interface to select and upload audio files (e.g., MP3, WAV, M4A).
Fast Transcription: Leverages the power of OpenAI's Whisper model for accurate and quick transcription.
RESTful Backend: Built with Java and Spring Boot to handle file processing and API communication securely.
Reactive Frontend: A smooth and responsive user experience built with React and Vite.
Decoupled Architecture: The frontend and backend are separate applications, allowing for independent development and scaling.

Tech Stack: 
Backend:
Java 17
Spring Boot 3
Spring AI
Maven

Frontend:
React
Vite
CSS3
API Service:
OpenAI Whisper API

Prerequisites:
Before you begin, ensure you have the following installed on your system:
Java Development Kit (JDK) 17 or later.
Apache Maven.
Node.js and npm (Node Package Manager).
An OpenAI API Key.

Getting Started:
Follow these instructions to get the project up and running on your local machine.

<img width="882" height="239" alt="image" src="https://github.com/user-attachments/assets/ff5f7b9b-5004-43d9-aed9-3594a0429dbd" />

. Configure Your API Key
This application requires an OpenAI API key to function.
Get your API key from the OpenAI Platform.
The backend is configured to read the key from an environment variable named OPENAI_API_KEY. You need to set this variable in the terminal where you will run the backend server.
<img width="872" height="396" alt="image" src="https://github.com/user-attachments/assets/3f86afad-8b96-4e1d-94db-2e5ee5025499" />

3. Run the Application
You need to run the backend and frontend servers in two separate terminals.

Terminal 1: Start the Backend Server ⚙️
Navigate to the backend directory
<img width="857" height="132" alt="image" src="https://github.com/user-attachments/assets/ac85f003-9ad3-4ca0-b833-1dc6a4266d3b" />

Run the Spring Boot application using the Maven wrapper:
<img width="863" height="137" alt="image" src="https://github.com/user-attachments/assets/c8d1f6e1-0c0c-4fa8-b23f-e5ecaf790a07" />

Terminal 2: Start the Frontend Server 🎨
Open a new terminal window.
Navigate to the frontend directory:
<img width="850" height="141" alt="image" src="https://github.com/user-attachments/assets/82b95dc3-41ff-4ba9-958f-0bfad76818a3" />

Install the necessary dependencies:
<img width="850" height="132" alt="image" src="https://github.com/user-attachments/assets/bd836694-ada0-484d-ac5e-03feddf77c7a" />

Start the Vite development server:
<img width="850" height="123" alt="image" src="https://github.com/user-attachments/assets/233a9a52-c689-48b1-b84e-ded96bbc0786" />

4. Access the Application
Open your web browser and navigate to http://localhost:5173.

You should now see the application running and be able to upload an audio file for transcription!


