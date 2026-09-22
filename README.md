# IFEX Frontend Node

This folder provides a Node.js server for the existing IFEX frontend. It serves the Vite production build as a standalone frontend and does not start or require the backend server.

## Commands

From this folder:

```bash
npm run build
npm start
```

Open `http://localhost:4173`.

The `build` script runs the existing frontend build and writes output to `frontend/dist`. React, routing, styling, and content remain in the original `frontend` project.
