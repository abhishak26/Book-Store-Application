# Book Store Application

A MERN stack book store app with an Express/MongoDB backend and a React/Vite frontend.

## Prerequisites

- Node.js 18 or newer
- npm
- A MongoDB Atlas cluster or local MongoDB instance

## Project Structure

- `backend/` - Express API and MongoDB connection
- `frontend/` - React UI built with Vite

## Setup

1. Clone the repository.
2. Install backend dependencies:

```bash
cd backend
npm install
```

3. Install frontend dependencies:

```bash
cd ../frontend
npm install
```

4. Update the MongoDB connection string in `backend/config.js` if you want to use your own Atlas cluster or local database.

## Run the App

Open two terminals:

### Backend

```bash
cd backend
npm run dev
```

The backend runs on port `5555`.

### Frontend

```bash
cd frontend
npm run dev
```

The frontend runs on the Vite dev server, usually at `http://localhost:5173/` or `http://localhost:5174/` if the default port is busy.

## Notes

- If the frontend port is already in use, Vite will automatically pick another available port.
- If MongoDB connection fails, verify the URI in `backend/config.js` and that your Atlas IP access list allows your machine.