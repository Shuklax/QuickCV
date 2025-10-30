# QuickCV

Smart feedback for your dream job — QuickCV helps you track applications and get AI-powered resume feedback.

![QuickCV Screenshot](/public/images/ss-01.png)

## Table of contents

- [Overview](#overview)
- [Features](#features)
- [Tech stack](#tech-stack)
- [Getting started](#getting-started)
	- [Prerequisites](#prerequisites)
	- [Install](#install)
	- [Development](#development)
	- [Build](#build)
- [Docker](#docker)
- [Folder structure](#folder-structure)
- [Contributing](#contributing)
- [Troubleshooting](#troubleshooting)
QuickCV is a small web application built with React and TypeScript. It lets users upload and track resumes, view AI-powered feedback (score breakdowns like ATS, tone, content, structure, and skills) and manage application entries in a clean UI.

The project is intended as a front-end demo / starter app and includes a simple data model, components, and styles based on Tailwind CSS.

- Routing using React Router + TypeScript
- Build-ready with Vite
- Dockerfile for containerized deployment

## Tech stack

- React (TypeScript)
- Vite
- React Router
### Prerequisites

- Node.js (v16+ recommended)

```powershell
npm install
```


```powershell
npm run dev
```

Open your browser at http://localhost:5173 (or the URL shown in the terminal).

### Build

Create a production build:

```powershell
npm run build
```

Preview the production build locally:

```powershell
npm run preview
```

## Docker

Build the Docker image (from the repository root):

```powershell
# build image
docker build -t quickcv:latest .

# run container (map ports if needed)
docker run -p 3000:3000 quickcv:latest
```

Note: adjust port mapping to your production hosting needs. The Dockerfile in this repo is a simple example for local container testing.

## Folder structure

Top-level layout (important files & folders):

```
.
├── app/                  # Main React application (components, routes, styles)
│   ├── components/       # Reusable UI components (Navbar, ResumeCard, ...)
│   ├── routes/           # Route components (home, resume pages)
│   └── app.css           # Tailwind + custom styles
├── constants/            # Sample data (resumes array)
├── public/               # Static assets (images, icons)
├── types/                # Global TypeScript declarations
├── Dockerfile
├── package.json
├── tsconfig.json
└── vite.config.ts
```

## Contributing

Contributions are welcome. A small suggested workflow:

1. Fork the repository
2. Create a branch for your feature (git checkout -b feat/name)
3. Make changes and add tests where appropriate
4. Run the dev server and verify locally
5. Open a PR with a clear description of changes

If you'd like, I can help add a CONTRIBUTING.md, GitHub Actions CI for lint/tests, or set up a pull request template.

## Troubleshooting

- If the dev server doesn't start, ensure Node and npm are installed and run `npm install` again.
- If styles don't apply, confirm Tailwind is running and that `app.css` is imported by the application entry.
- If images are missing, check `public/images/` and the `imagePath` values in `constants/index.ts`.

## License

This project is provided under the MIT License. See the `LICENSE` file for details (or tell me if you want me to add one).

---

If you'd like, I can also:


Tell me which of those you'd like next and I will implement it.
A QuickCV

A modern, production-ready template for building full-stack React applications using React Router.
[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/remix-run/react-router-templates/tree/main/default)

## Features
- 📦 Asset bundling and optimization
- 🔄 Data loading and mutations
- 🔒 TypeScript by default
- 🎉 TailwindCSS for styling
- 📖 [React Router docs](https://reactrouter.com/)

## Getting Started

### Installation

Install the dependencies:

```bash
npm install
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```

## Deployment

### Docker Deployment

To build and run using Docker:

```bash
docke build -t my-app .

# Run the container
docke run -p 3000:3000 my-app
```

The containerized application can be deployed to any platform that supports Docker, including:

- AWS ECS
- Google Cloud Run
- Azure Container Apps
- Digital Ocean App Platform
- Fly.io
- Railway
# QuickCV

Smart feedback for your dream job — QuickCV helps you track applications and get AI-powered resume feedback.

![QuickCV Screenshot](/public/images/resume-1.png)

## Table of contents

- [Overview](#overview)
- [Features](#features)
- [Tech stack](#tech-stack)
- [Getting started](#getting-started)
	- [Prerequisites](#prerequisites)
	- [Install](#install)
	- [Development](#development)
	- [Build](#build)
- [Docker](#docker)
- [Folder structure](#folder-structure)
- [Contributing](#contributing)
- [Troubleshooting](#troubleshooting)
- [License](#license)

## Overview

QuickCV is a small web application built with React and TypeScript. It lets users upload and track resumes, view AI-powered feedback (score breakdowns like ATS, tone, content, structure, and skills) and manage application entries in a clean UI.

The project is intended as a front-end demo / starter app and includes a simple data model, components, and styles based on Tailwind CSS.

## Features

- List and view resume entries
- Per-resume feedback breakdown (overall score, ATS, tone & style, content, structure, skills)
- Responsive layout with Tailwind CSS
- Routing using React Router + TypeScript
- Build-ready with Vite
- Dockerfile for containerized deployment

## Tech stack

- React (TypeScript)
- Vite
- React Router
- Tailwind CSS
- esbuild (dev tooling)
- Docker (for containerization)

## Getting started

### Prerequisites

- Node.js (v16+ recommended)
- npm (or pnpm/yarn)
- Docker (optional, only if you want to build the container)

### Install

Open a terminal in the project root (`c:\Users\harsh\Desktop\QuickCV`) and run:

```powershell
npm install
```

### Development

Start the development server (Vite):

```powershell
npm run dev
```

Open your browser at http://localhost:5173 (or the URL shown in the terminal).

### Build

Create a production build:

```powershell
npm run build
```

Preview the production build locally:

```powershell
npm run preview
```

## Docker

Build the Docker image (from the repository root):

```powershell
# build image
- Railway

# run container (map ports if needed)

```

Note: adjust port mapping to your production hosting needs. The Dockerfile in this repo is a simple example for local container testing.

## Folder structure

Top-level layout (important files & folders):

```
.
├── app/                  # Main React application (components, routes, styles)
│   ├── components/       # Reusable UI components (Navbar, ResumeCard, ...)
│   ├── routes/           # Route components (home, resume pages)
│   └── app.css           # Tailwind + custom styles
├── constants/            # Sample data (resumes array)
├── public/               # Static assets (images, icons)
├── types/                # Global TypeScript declarations
├── Dockerfile
├── package.json
├── tsconfig.json
└── vite.config.ts
```

## Contributing

Contributions are welcome. A small suggested workflow:

1. Fork the repository
2. Create a branch for your feature (git checkout -b feat/name)
3. Make changes and add tests where appropriate
4. Run the dev server and verify locally
5. Open a PR with a clear description of changes

If you'd like, I can help add a CONTRIBUTING.md, GitHub Actions CI for lint/tests, or set up a pull request template.

## Troubleshooting

- If the dev server doesn't start, ensure Node and npm are installed and run `npm install` again.
- If styles don't apply, confirm Tailwind is running and that `app.css` is imported by the application entry.
- If images are missing, check `public/images/` and the `imagePath` values in `constants/index.ts`.

## License

This project is provided under the MIT License. See the `LICENSE` file for details (or tell me if you want me to add one).

---

If you'd like, I can also:

- Add badges (build, license, version)
- Create a short demo GIF and include it in the README
- Add basic unit tests and CI

Tell me which of those you'd like next and I will implement it.
### DIY Deployment

If you're familiar with deploying Node applications, the built-in app server is production-ready.

Make sure to deploy the output of `npm run build`

```
├── package.json
├── package-lock.json (or pnpm-lock.yaml, or bun.lockb)
├── build/
│   ├── client/    # Static assets
│   └── server/    # Server-side code
```

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever CSS framework you prefer.

---

Built with ❤️ using React Router.
