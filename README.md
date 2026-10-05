# CodePulse Bookings

A React-based booking and scheduling web application built for CodePulse. The application provides a clean interface for managing booking workflows and communicates with a separate backend REST API.

## Live Demo

**Frontend:** https://frontend-chi-swart-59.vercel.app

## Features

- Interactive booking and scheduling interface
- Calendar and date selection
- Client-side routing with React Router
- REST API integration using Axios
- Responsive web interface
- Production frontend deployment through Vercel
- Separate frontend and backend architecture

## Tech Stack

### Frontend

- React
- JavaScript
- React Router
- Axios
- React Multi Date Picker
- Font Awesome
- React Icons
- CSS

### Deployment

- **Frontend:** Vercel
- **Backend API:** Render

## Architecture

The application uses a separated frontend/backend architecture.

```text
User
  |
  v
React Frontend
  |
  | HTTP / REST API requests
  v
Backend API
  |
  v
Application Data
```

The React frontend handles the user interface, navigation, booking interactions, and date selection. Axios is used to communicate with the backend API.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm

### Installation

Clone the repository:

```bash
git clone https://github.com/ajsarks/codepulse-bookings-frontend.git
cd codepulse-bookings-frontend
```

Install the dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

The application will be available at:

```text
http://localhost:3000
```

## Available Scripts

### `npm start`

Runs the application in development mode.

### `npm test`

Starts the test runner in interactive watch mode.

### `npm run build`

Creates an optimized production build in the `build` directory.

## Project Structure

```text
codepulse-bookings-frontend/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   └── ...
├── package.json
├── package-lock.json
└── README.md
```

## API Integration

The frontend communicates with the CodePulse backend through HTTP requests using Axios.

For local development, API requests are proxied to the deployed backend server.

## Deployment

The frontend is deployed using Vercel.

Production builds can be generated with:

```bash
npm run build
```

## Purpose

CodePulse Bookings was developed to provide a web-based interface for organizing and managing booking workflows while keeping the frontend and backend services independently deployable and maintainable.
