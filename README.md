# AI Chatbot Application

A modern and interactive chatbot application built with React and Node.js, using Google's Gemini AI model.

## Features

- Beautiful and responsive UI
- Real-time chat interface
- Powered by Google Gemini AI
- Smooth animations and transitions
- Error handling and loading states

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- Google Gemini API key

## Setup

1. Clone the repository
2. Install backend dependencies:
   ```bash
   npm install
   ```
3. Install frontend dependencies:
   ```bash
   cd client
   npm install
   ```
4. Create a `.env` file in the root directory and add your Google Gemini API key:
   ```
   GOOGLE_API_KEY=your_api_key_here
   PORT=5000
   ```

## Running the Application

1. Start the backend server:
   ```bash
   npm run dev
   ```
2. In a new terminal, start the frontend:
   ```bash
   npm run client
   ```
3. Open your browser and navigate to `http://localhost:3000`

## Deployment

To deploy the application:

1. Build the React frontend:
   ```bash
   cd client
   npm run build
   ```
2. Deploy the backend to your preferred hosting service (e.g., Heroku, AWS, etc.)
3. Update the API URL in the frontend code to point to your deployed backend
4. Deploy the frontend to a static hosting service (e.g., Netlify, Vercel, etc.)

## Technologies Used

- React.js
- Material-UI
- Node.js
- Express
- Google Gemini AI
- Axios

## License

MIT 