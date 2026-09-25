# MPLADS AI Monitoring Demo

A demo dashboard for exploring MPLADS-style project data, risk indicators, audit workflows, and dataset uploads.

## Live Demo

[Open the live application](http://13.48.137.1:3000/)

> The public demo uses plain HTTP and demo credentials/data. Do not submit real, confidential, or personal information, or reuse a password you use elsewhere.

## Run Locally

### Requirements

- Node.js 18 or newer
- npm

From the repository root:

```sh
npm install
npm run dev
```

Open `http://localhost:3000`. The Express server serves the React app and API from the same process. Press `Ctrl+C` to stop it.

To build and check the app:

```sh
npm run build
npm run lint
```

To run the production build locally after building:

```sh
# PowerShell
$env:NODE_ENV = "production"
npm start
```

```sh
# macOS / Linux
NODE_ENV=production npm start
```

## Included

- Project dashboard with risk levels, alerts, and project details.
- Audit review status, notes, evidence checklist, and case workflows.
- Dataset upload and analysis demo flows.
- Role-based demo views and generated sample projects.

This repository is a demonstration application, not an official government system or a production audit service. Risk and anomaly indicators are prompts for human review, not findings of fraud or wrongdoing. The demo server uses sample data and in-memory state; changes may reset when it restarts.