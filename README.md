# VibeCheck-David

VibeCheck-Libunao,Elegido is an app that interacts with a Node.js backend to deliver fortunes, jokes, mood vibes, and a "SMASH" counter. It's designed for learning frontend-backend communication using APIs.

## Features

- **Fortune** - Get a random developer-friendly fortune.
- **Joke** - Receive a random programming joke.
- **Mood Vibes** - Choose a mood to get a motivational message.
- **SMASH!** - Increment a counter to track "smashes."

## Installation and Setup

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Backend Setup
\`\`\`bash
cd backend
npm install
npm start
\`\`\`

### Frontend Setup
\`\`\`bash
cd frontend
# Open index.html in browser or use a local server
\`\`\`

## API Endpoints

1. **GET /fortune** - Returns a random fortune
2. **GET /joke** - Returns a random programming joke
3. **POST /mood** - Accepts mood and returns motivational message
4. **GET /smash** - Returns current smash count
5. **POST /smash** - Increments smash counter

## Usage

1. Start the backend server
2. Open the frontend in a browser
3. Use the interface to get fortunes, jokes, set mood, and smash!

## Screenshots

*PASTE SCREENSHOT HERE*

## Project Structure

- `/backend` - Node.js server with Express
- `/frontend` - HTML, CSS, and JavaScript frontend
- `README.md` - This file

## Contributing

1. Fork the repository
2. Create a feature branch (\`git checkout -b feature/AmazingFeature\`)
3. Commit your changes (\`git commit -m 'Add some AmazingFeature'\`)
4. Push to the branch (\`git push origin feature/AmazingFeature\`)
5. Open a Pull Request
