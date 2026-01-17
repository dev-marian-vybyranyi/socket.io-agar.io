# Agar.io Clone

A multiplayer game clone of Agar.io built with Node.js, Express, and Socket.io.

## Installation

1. Install dependencies:
   ```bash
   npm install
   ```

## Running the Server

Start the server on port 9000:

```bash
npm run start
```

Then open your browser and navigate to `http://localhost:9000`.

## Project Structure

- `servers.js`: Main entry point, initializes Express and Socket.io.
- `public/`: Contains static files (HTML, CSS, client-side JS).
- `socketStuff/`: Socket.io logic and event handlers.
- `expressStuff/`: Express configuration.
- `index.js`: Loads the main modules.
