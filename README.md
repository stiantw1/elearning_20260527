# E-Learning AI App

This repository contains a React + Vite application with an Express backend. It is ready to deploy to any standard Node hosting platform such as Render.

## Run Locally

**Prerequisites:** Node.js

1. Install dependencies:
   `npm install`
2. Create a `.env` file in the project root and add your Gemini API key:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```
3. Run the app in development mode:
   `npm run dev`

## Build for Production

1. Build the frontend and backend:
   `npm run build`
2. Start the production server:
   `npm start`

## Render Deployment

For Render, use these commands:

- Build Command: `npm run build`
- Start Command: `npm start`

Render will provide the `PORT` environment variable automatically, and the app is configured to use it.

### Environment Variables

- `GEMINI_API_KEY`: Your Google Gemini API key

Create a `.env` file at the project root for local development. The `.gitignore` is already configured to ignore `.env` files, but includes `.env.example` for reference.

If you deploy to Render, set this variable in the service dashboard instead of using `.env`.
