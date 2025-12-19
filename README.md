# Paralel Life - Frontend

Frontend application built with React, Vite, and TailwindCSS.

## Prerequisites

- Node.js (v18 or higher)
- npm or yarn

## Installation

```bash
npm install
```

## Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_URL=http://localhost:3000/api
VITE_GOOGLE_CLIENT_ID=your_google_client_id
```

## Development

```bash
npm run dev
```

The application will run on `http://localhost:5173`

## Build

```bash
npm run build
```

## Preview Production Build

```bash
npm run preview
```

## Project Structure

```
frontend/
├── public/          # Static assets
├── src/
│   ├── components/  # Reusable components
│   ├── context/     # React context providers
│   ├── pages/       # Page components
│   ├── services/    # API services
│   ├── App.jsx      # Main app component
│   └── main.jsx     # Entry point
├── index.html       # HTML template
└── vite.config.js   # Vite configuration
```

## Technologies

- **React** - UI library
- **Vite** - Build tool
- **TailwindCSS** - Styling
- **React Router** - Routing
- **Axios** - HTTP client
- **Lucide React** - Icons
