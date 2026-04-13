# Scrum Board

A browser-based scrum board for organizing project tasks across **To Do**, **In Progress**, **On Hold**, and **Done**. Tasks persist in `localStorage`, so your board survives refreshes on the same device and browser.

## Features

- Create tasks with a title and description
- Drag cards between columns or use **Ship to next** to advance status
- Remove tasks from any column
- Dark / light theme toggle (preference is stored locally)
- **Done** column shows how long each task spent in progress before completion

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)

## Setup

```bash
npm install
```

## Run locally

```bash
npm start
```

This starts [live-server](https://www.npmjs.com/package/live-server) on port **8181**, bound to all interfaces (`0.0.0.0`). Open:

- [http://localhost:8181](http://localhost:8181)

The dev server watches files and reloads the page when assets change.

## Project layout

| Path | Role |
|------|------|
| `index.html` | App shell and board markup |
| `server.js` | Dev server configuration |
| `app/js/` | Client JavaScript (ES modules) |
| `app/css/` | Styles and design tokens |

## License

This repository does not include a license file. Add one if you plan to distribute or reuse the code.
