Name: Harman Singh    Uid:24BCF10046      Section: 24BCF-1(A)

# Calendar4 — React + Vite Calendar & Posts Demo

## Project Overview
This is a small React application scaffolded with Vite that demonstrates a calendar view and a simple posts UI. It uses React, Redux Toolkit, and axios for data fetching. The app is intended as a learning/demo project showing how to combine a calendar component with a posts list and API integration.

## How it works
- The app is built with Vite and React (entry: `main.jsx`).
- `src/components/calendar.jsx` renders the calendar UI (uses `react-big-calendar` and `date-fns`).
- `src/components/postCard.jsx` renders individual post items.
- `src/Api/postApi.js` contains API calls (uses `axios`).
- `src/features/posts/postSlice.jsx` contains Redux Toolkit logic for posts state.
- Routing and pages live under `src/pages/` (main page: `Home.jsx`).

## Start (Development)
Prerequisites: Node.js (recommended >= 16) and npm.

1. Install dependencies:

	npm install

2. Start the dev server:

	npm run dev

3. Open the app in your browser at http://localhost:5173

Available scripts (from `package.json`):
- `npm run dev` — start Vite dev server
- `npm run build` — build for production
- `npm run preview` — preview the production build
- `npm run lint` — run ESLint

To run tests (Vitest is installed but no npm script):

	npx vitest

## Usage / What you can do with this project
- View and interact with the calendar UI to inspect dates and events.
- Browse, create (if wired to an API), and inspect posts rendered via `postCard.jsx`.
- Use this as a starter template to add event persistence, authentication, or a backend.

## Project Structure (important files)
- `src/components/calendar.jsx` — calendar component
- `src/components/postCard.jsx` — post display card
- `src/Api/postApi.js` — API helper functions
- `src/features/posts/postSlice.jsx` — Redux slice for posts
- `src/pages/Home.jsx` — main page that composes components

## Notes
- Tests are in `src/tests/` and `tests/` — run with `npx vitest`.
- If you want a `test` npm script, add: `"test": "vitest"` to `package.json`.

---
Name: Harman    Section: 24BCF-1(A)    Rollno: 24BCF10046