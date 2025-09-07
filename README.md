# Zoom_frontend (React + Vite)

A minimal React + Vite frontend for a WebRTC/Socket.IO video-calling app.

## Scripts
npm install
npm run dev        # local dev (default: http://localhost:5173)
npm run build      # creates production build in /dist
npm run preview    # serve built files locally

## Env (Vite)
Create `.env` and set:
VITE_API_URL=https://<your-backend>.onrender.com
VITE_SOCKET_URL=wss://<your-backend>.onrender.com  # if using Socket.IO/WebSocket

## Deploy (Render Static Site)
- Build Command: `npm ci && npm run build`
- Publish Directory: `dist`
- Redirects/Rewrites: `/* -> /index.html` (Rewrite)

## Tech
- React, Vite, (optionally) Socket.IO client / WebRTC

