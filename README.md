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
- 		cd Interv-AI

	2.	Set up the backend:
		Navigate to the backend folder:
-    		cd backend

       	Install dependencies:
- 	 	pip install -r requirements.txt

     	Start the backend server:
	      	flask run
	
	3.	Set up the frontend:
 		Navigate to the frontend folder:
-    		cd frontend

       	Install dependencies:
- 	 	npm install

     	Start the React development server:
-        	npm start

   		Open your browser and go to:
-      		http://localhost:3000


To format your GitHub README properly with code blocks, you need to use Markdown syntax. Specifically, you can wrap your code sections in triple backticks (```). Here’s how your content will look when formatted for GitHub:

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

Tips for Markdown Formatting on GitHub

	•	Use triple backticks (```) to create code blocks.
	•	Use - or * for bullet points.
	•	Use #, ##, or ### for headers.

You can copy and paste this directly into your GitHub README file for proper formatting! 😊

     
