# Your Platform For Online Complaints

> A simple online complaints platform with separate backend and React frontend for users, agents and admins.

## Project Overview

This repository contains a full-stack application for filing and tracking complaints. It provides:
- User-facing complaint submission and status pages
- Agent dashboard for handling complaints
- Admin views for user/agent management
- Real-time or near-real-time chat/support components

## Features

- Submit complaints with details and attachments
- Track complaint status and history
- Agent assignment and response handling
- Admin management (users, agents)
- Basic chat between users and agents

## Repository Structure

- `backend/` — Node.js backend (API, DB schema, config)
- `frontend/` — React frontend (components for user, agent, admin)
- `Demo Video/` — demo resources
- `Documentation/` — design and docs

## Prerequisites

- Node.js (16+ recommended)
- npm or yarn
- MongoDB or configured DB used by `backend/` (see `Schema.js`)

## Backend: quick start

1. Open a terminal and go to the `backend` folder:

```powershell
cd backend
```

2. Install dependencies:

```powershell
npm install
```

3. Create or update environment variables (example):

- `PORT` — port to run the API (default 5000)
- `MONGO_URI` — MongoDB connection string
- `JWT_SECRET` — secret for auth tokens

Create a `.env` file in `backend/` with values above.

4. Run the backend:

```powershell
npm start
```

The server should start on the configured port. Check `index.js` and `config.js` for additional settings.

## Frontend: quick start

1. Open a terminal and go to the `frontend` folder:

```powershell
cd frontend
```

2. Install dependencies:

```powershell
npm install
```

3. Start the React dev server:

```powershell
npm start
```

4. The app typically opens at `http://localhost:3000`.

Update any API base URLs in `frontend/src` if your backend runs on a different host/port.

## Environment / Configuration

- Backend configuration files: `backend/config.js`, `backend/Schema.js`.
- Frontend environment: edit API URLs in `frontend/src` components or create a `.env` in `frontend/` per Create React App conventions.

## File references

- See `backend/index.js` for server entry.
- See `frontend/src/App.js` for main React routing.

## Contributing

1. Create an issue describing your change.
2. Open a branch, implement the change, run the app to verify.
3. Submit a pull request with a clear description.

## License & Contact

This project currently has no formal license file in the repo. Add a `LICENSE` if you want to set one.

For questions contact the maintainers or open an issue in this repository.
# Your-Platform-For-Online-Complaints