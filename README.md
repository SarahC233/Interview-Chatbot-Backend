# Interview Skills Chatbot Backend

This is the backend for the Interview Skills Chatbot, which powers the chatbot logic and AI-based interview question generation. The backend works in conjunction with the frontend, deployed here: [Interview Chatbot Frontend](https://sarahc233.github.io/Interview-Chatbot-Frontend/).

## Overview

- The backend handles communication with the AI service, processes user inputs, and generates interview questions based on the selected job field.
- It uses the Google Gemini API to provide real-time interview practice and feedback.

## Installation

1. Clone the repository:

   `git clone https://github.com/SarahC233/Interview-Chatbot-Backend.git`

2. Install dependencies:

   `npm install`

3. Create a `.env` file and add the following:

`GOOGLE_GEMINI_API_KEY=your_google_gemini_api_key DATABASE_URL=your_database_url PORT=your_desired_port (optional, defaults to 3001)`

4. Run the server:

`npm start`

The backend will run on `http://localhost:3001`.

## Deployment

This backend powers the frontend deployed at: [Interview Chatbot Frontend](https://sarahc233.github.io/Interview-Chatbot-Frontend/).



