# Smart Recipe Generator

A MERN stack web application that helps users discover recipes based on available ingredients and dietary preferences, powered by AI.

## Project Structure

```
smart-recipe-generator/
├── backend/          # Express.js backend API
│   ├── src/
│   ├── package.json
│   └── .env.example
├── frontend/         # React frontend
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── .env.example
└── README.md
```

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file based on `.env.example`:
   ```bash
   cp .env.example .env
   ```

4. Update the `.env` file with your configuration:
   - MongoDB connection string
   - Gemini AI API key
   - JWT secret

5. Start the development server:
   ```bash
   npm run dev
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file based on `.env.example`:
   ```bash
   cp .env.example .env
   ```

4. Start the development server:
   ```bash
   npm start
   ```

The frontend will run on `http://localhost:3000` and the backend on `http://localhost:5000`.

## Features

- AI-powered recipe generation using Gemini AI
- Search recipes by ingredients
- Filter by dietary preferences, difficulty, and cooking time
- Save favorite recipes
- Rate recipes
- Personalized recommendations
- Mobile-responsive design

## Tech Stack

**Frontend:**
- React 18
- React Router
- Axios
- Tailwind CSS

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT authentication
- bcrypt for password hashing
- Google Generative AI (Gemini)

## Testing

Run tests in both frontend and backend:

```bash
# Backend tests
cd backend
npm test

# Frontend tests
cd frontend
npm test
```

## License

ISC
