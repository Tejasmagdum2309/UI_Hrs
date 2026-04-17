# my-project

Vite + React + TypeScript app with Tailwind CSS, React Router, and React Hook Form (login, signup, dashboard).

## Prerequisites

- [Node.js](https://nodejs.org/) **18+** (LTS recommended)
- npm (comes with Node.js)

Check versions:

```bash
node -v
npm -v
```

## Run locally

1. **Go to the project folder**

   ```bash
   cd my-project
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the dev server**

   ```bash
   npm run dev
   ```

4. **Open the app** — the terminal prints a local URL (usually `http://localhost:5173`). Open it in your browser.

The app redirects `/` to `/login`. After a successful login, you are sent to `/dashboard`.

## Other scripts

| Command | Description |
|--------|-------------|
| `npm run build` | Typecheck and production build to `dist/` |
| `npm run preview` | Serve the production build locally |
| `npm run lint` | Run ESLint |

## Tech stack

- React 19, TypeScript, Vite
- Tailwind CSS v4
- `react-router-dom` — routing
- `react-hook-form` — forms on login/signup pages
