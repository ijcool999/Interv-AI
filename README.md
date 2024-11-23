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


Usage

Candidate Workflow

	1.	Login or Register: Candidates log in to access the platform.
	2.	Assessment Rounds:
	•	Round 1 (Aptitude): Answer multiple-choice questions within a timer.
	•	Round 2 (Technical Quiz): Solve domain-specific technical problems.
	•	Round 3 (Coding Round): Write and submit code for programming challenges.
	3.	Feedback & Report: Receive detailed feedback and download the performance report.

Admin Features (Future Scope)

	•	Monitor candidate progress.
	•	Add or modify question templates.
	•	View candidate reports and performance summaries.


 Contributing

We welcome contributions to make IntervAI better! 

Future Enhancements

	•	Proctoring module integration for live candidate monitoring.
	•	Admin dashboard for managing questions and candidates.
	•	Advanced analytics for evaluating overall trends in candidate performance.

Contact

For any questions or contributions, feel free to reach out at ishanjain2174@gmail.com or open an issue in this repository.
