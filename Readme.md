# AI Code Reviewer

## Overview

AI Code Reviewer is a web-based application that utilizes Google Gemini AI to analyze and review code. It provides AI-driven code suggestions, error detection, and optimization insights. The project is built using Node.js for the backend and React Vite for the frontend.

## Features

- **AI-powered Code Analysis**: Uses Google Gemini AI for reviewing and suggesting improvements.
- **Real-time Feedback**: Provides instant suggestions and optimizations.
- **Syntax and Error Detection**: Identifies syntax errors and potential bugs.
- **Multi-language Support**: Can review code written in different programming languages.
- **User-friendly Interface**: Built with React Vite for a fast and smooth user experience.

## Tech Stack

### Frontend:

- React Vite
- HTML, CSS, JavaScript
- Axios for API requests
- React-markdown for code output functionality
- React-simple-code-editer for edit your code
- Rehype- highlight for highlight your code by gemini ai

### Backend:

- Node.js
- Express.js
- Google Gemini AI API
- MongoDB (if required for storing reviews and user data)

## Installation

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm or yarn
- MongoDB (optional, if using a database)

### Steps

1. **Clone the repository**:

   ```sh
   git clone https://github.com/Shubham91998/AI-Code-reviewer.git
   cd ai-code-reviewer
   ```

2. **Install dependencies**:

   ```sh
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file and add the necessary API keys and configuration:

   ```env
   GEMINI_API_KEY=your_google_gemini_api_key
   PORT=your port no.
   ```

4. **Start the backend server**:

   ```sh
   cd backend
   npm start
   ```

5. **Start the frontend**:

   ```sh
   cd frontend
   npm run dev
   ```

## API Endpoints

| Method | Endpoint   | Description                 |
| ------ | ---------- | --------------------------- |
| POST   | `/ai/reviewer`  | Sends code to AI for review |
| 

## Usage

1. Open the frontend in your browser.
2. Paste your code in the input field.
3. Click the "Review Code" button to get AI-powered feedback.
4. Review the suggestions and optimize your code accordingly.

## Contributing

Feel free to contribute by submitting pull requests. Make sure to follow best coding practices and provide detailed documentation.

## License

This project is licensed under the MIT License.

