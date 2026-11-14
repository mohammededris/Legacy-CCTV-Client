# Legacy CCTV Client

Frontend for the **Legacy CCTV Edge-AI Gateway** — an AI-powered monitoring system that retrofits existing analog CCTV cameras with local person detection, tracking, and event alerts (no cloud, no camera replacement).

## Tech Stack

- [React 19](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vite.dev/)
- [ESLint](https://eslint.org/)

## Getting Started

Requires [Node.js](https://nodejs.org/).

```bash
npm install
npm run dev
```

The dev server starts at `http://localhost:5173` with hot module replacement.

## Scripts

| Command           | Description                                                      |
| ----------------- | ---------------------------------------------------------------- |
| `npm run dev`     | Start the Vite dev server                                        |
| `npm run build`   | Type-check with `tsc -b`, then build for production into `dist/` |
| `npm run preview` | Serve the production build locally                               |
| `npm run lint`    | Run ESLint over the project                                      |

## Project Structure

```
├── index.html          # App entry HTML
├── src/
│   ├── main.tsx        # React entry point
│   ├── App.tsx         # Root component
│   ├── App.css
│   ├── index.css
│   └── assets/
└── public/
```

## Status

Initial scaffold. The client UI for camera feeds, event alerts, and system health. The corresponding backend (Express 5 on Bun) lives in the `Legacy-CCTV-Server` repository.
