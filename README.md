# AI Learning Assistant

## Overview
The AI Learning Assistant is a comprehensive platform designed to revolutionize the way students and educators interact with learning materials. It leverages AI-powered tools to generate quizzes, evaluate answers, track progress, and facilitate communication through forums and chat features.

## Features

### Document Processing
- **Read Out Loud**: Converts text to speech for better accessibility.
- **Process PDF Document**: Extracts text from uploaded PDFs.
- **Generate Questions**: Automatically creates quizzes from study materials.
- **Download Questions**: Export generated questions as a PDF.
- **Upload PDF**: Upload textbooks or study materials for processing.

### Learning Features
- **Track Progress**: Monitor learning progress with detailed analytics.
- **View Analytics**: Visualize performance trends and scores.
- **Evaluate Answers**: Get instant feedback on written answers.
- **Search**: Perform web searches for academic queries.
- **Voice Commands**: Control the application using voice commands.

### Authentication
- **Login**: Secure login for users.
- **Register Account**: Create a new account.
- **Password Reset**: Reset forgotten passwords.
- **Social Login**: Login using Google.

### Forum & Chat
- **Chat**: Interact with peers and educators.
- **Report Message**: Report inappropriate messages.
- **Create Thread**: Start new discussion threads.
- **View Threads**: Browse existing threads.
- **Post Message**: Contribute to discussions.

## Installation

### Backend
1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start the server:
   ```bash
   python server.py
   ```

### Frontend
1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

## Usage
1. Open the frontend in your browser at `http://localhost:3000`.
2. Use the platform to upload PDFs, generate questions, evaluate answers, and more.

## Environment Variables

### Backend
Create a `.env` file in the `backend` directory with the following variables:
```
GEMINI_API_KEY=<your_gemini_api_key>
FLASK_ENV=development
```

### Frontend
Add Firebase configuration in `src/firebase.js`.

## Technologies Used
- **Frontend**: React, Tailwind CSS, Framer Motion
- **Backend**: Flask, PyPDF2, Google Generative AI
- **Database**: In-memory storage (can be extended to use a database)

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- [Google Generative AI](https://ai.google/) for powering the AI features.
- [React](https://reactjs.org/) for the frontend framework.
- [Flask](https://flask.palletsprojects.com/) for the backend framework.