IntervAI : Coding Assessment Platform

This project is a web-based coding assessment platform designed to evaluate candidates’ coding skills through automated tests. It dynamically generates coding questions, allows candidates to write their code, evaluates their code for correctness, and provides real-time feedback.

Features

	•	Dynamic Question Generation: Coding questions are dynamically generated using the Gemini API.
	•	Code Submission: Candidates can submit their code, and the system evaluates the correctness of the solution.
	•	Real-Time Feedback: After submission, candidates receive feedback, including score and detailed insights into their code quality, efficiency, and correctness.
	•	Automatic Evaluation: Non-code answers such as “I don’t know” are automatically scored 0, and valid code submissions are evaluated using an AI model.
	•	Timer: A countdown timer is displayed for each round to keep candidates on track.
	•	Total Score & Feedback: After all rounds, the system aggregates the scores from all coding questions and stores the total score and overall feedback in a MongoDB database.

Tech Stack

	•	Frontend: React.js
	•	Backend: Flask, Python
	•	Database: MongoDB
	•	API Integration: Gemini API for generating questions and evaluating code
	•	State Management: React hooks (useState, useEffect, useCallback)
	•	Styling: CSS (Custom styles)

Installation

Prerequisites

	1.	MongoDB: You should have MongoDB running locally or on a remote server.
	2.	Python: Ensure Python (preferably 3.x) is installed on your machine.
	3.	Node.js and npm: For running the React frontend.
Here is the properly formatted content ready to paste into your GitHub README file:

Installation

Prerequisites

Before setting up the project, ensure the following are installed:
	1.	MongoDB: You should have MongoDB running locally or on a remote server.
	2.	Python: Ensure Python (preferably 3.x) is installed on your machine.
	3.	Node.js and npm: Required for running the React frontend.

Setup Backend (Flask)

	1.	Clone the Repository:

git clone https://github.com/ijcool999/Interv-AI.git
cd Interv-AI


	2.	Navigate to the Backend Folder:

cd backend


	3.	Install Dependencies:

pip install -r requirements.txt


	4.	Start the Backend Server:

flask run

The backend server will be running at:

http://127.0.0.1:8080

Setup Frontend (React)

	1.	Navigate to the Frontend Folder:

cd frontend


	2.	Install Dependencies:

npm install


	3.	Start the React Development Server:

npm start

Open your browser and go to:

http://localhost:3000

How to Use This

You can paste this directly into your README file on GitHub. It will render with proper formatting, including code blocks for terminal commands. Let me know if you need further assistance! 😊
