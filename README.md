Audio to Text Transcriber 🎧
A full-stack web application that transcribes audio files to text using a Spring Boot backend and a React frontend. The transcription is powered by OpenAI's Whisper API.

Of course! Here is a complete README.md file for your project, written in Markdown. You can copy and paste this directly into a README.md file in the root of your project folder.

Audio to Text Transcriber 🎧
A full-stack web application that transcribes audio files to text using a Spring Boot backend and a React frontend. The transcription is powered by OpenAI's Whisper API.

✨ Features
Simple File Upload: A clean interface to select and upload audio files (e.g., MP3, WAV, M4A).

Fast Transcription: Leverages the power of OpenAI's Whisper model for accurate and quick transcription.

RESTful Backend: Built with Java and Spring Boot to handle file processing and API communication securely.

Reactive Frontend: A smooth and responsive user experience built with React and Vite.

Decoupled Architecture: The frontend and backend are separate applications, allowing for independent development and scaling.

🛠️ Tech Stack
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

📋 Prerequisites
Before you begin, ensure you have the following installed on your system:

Java Development Kit (JDK) 17 or later.

Apache Maven.

Node.js and npm (Node Package Manager).

An OpenAI API Key.

🚀 Getting Started
Follow these instructions to get the project up and running on your local machine.

1. Clone the Repository
Bash

git clone https://github.com/introspectivepen/Audio-transcriber-java-springboot-springApi.git
cd Audio-transcriber-java-springboot-springApi
2. Configure Your API Key
This application requires an OpenAI API key to function.

Get your API key from the OpenAI Platform.

The backend is configured to read the key from an environment variable named OPENAI_API_KEY. You need to set this variable in the terminal where you will run the backend server.

On Windows (PowerShell):

PowerShell

$env:OPENAI_API_KEY="sk-YourSecretApiKey"
On macOS/Linux:

Bash

export OPENAI_API_KEY=sk-YourSecretApiKey
Important: You must set this variable every time you open a new terminal to run the backend, or set it globally on your system.

3. Run the Application
You need to run the backend and frontend servers in two separate terminals.

Terminal 1: Start the Backend Server ⚙️
Navigate to the backend directory:

Bash

cd audio-transcribe
Run the Spring Boot application using the Maven wrapper:

Bash

./mvnw spring-boot:run
The backend server will start on http://localhost:8080.

Terminal 2: Start the Frontend Server 🎨
Open a new terminal window.

Navigate to the frontend directory:

Bash

cd audio-transcribe-frontend
Install the necessary dependencies:

Bash

npm install
Start the Vite development server:

Bash

npm run dev
The frontend server will start on http://localhost:5173 (or another port if 5173 is busy).

4. Access the Application
Open your web browser and navigate to http://localhost:5173. You should now see the application running and be able to upload an audio file for transcription!
