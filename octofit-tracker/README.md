# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js/Express, and MongoDB.

## Architecture

```
octofit-tracker/
├── frontend/          # React 19 + Vite (Port 5173)
├── backend/           # Node.js + Express + TypeScript (Port 8000)
└── mongodb/           # MongoDB Instance (Port 27017)
```

## Getting Started

### Prerequisites

- Node.js 18+
- MongoDB 5.0+
- npm or yarn

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

Frontend runs on `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```

Backend runs on `http://localhost:8000`

### MongoDB Setup

```bash
# Start MongoDB locally
mongod --port 27017
```

MongoDB runs on `mongodb://localhost:27017/octofit-tracker`

## API Endpoints

- `GET /` - API status
- `GET /api/health` - Health check

## Tech Stack

- **Frontend:** React 19, Vite, TypeScript
- **Backend:** Express.js, TypeScript, Node.js
- **Database:** MongoDB, Mongoose ODM
- **Styling:** CSS

## Development

Both frontend and backend are configured with:
- TypeScript for type safety
- ESLint for code quality
- Environment-based configuration

## Ports

- Frontend: `5173` (Vite dev server)
- Backend: `8000` (Express API server)
- MongoDB: `27017` (Database)

## License

MIT
