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

Setup Backend (Flask)

	1.	Clone the repository:
 		git clone https://github.com/ijcool999/Interv-AI.git
		cd Interv-AI

	2.	Set up the backend:
		Navigate to the backend folder:
   		cd backend

       	Install dependencies:
	 	pip install -r requirements.txt

     		Start the backend server:
     
