# SomaAI

SomaAI is a web-based AI application powered by TypeScript, HTML, and Firebase, located in the `SomaAI` folder of the Lord-LLM/AI_Engineering repository. Its core is a modern TypeScript front-end, leveraging Vite for development/build, and is optionally integrated with Firebase for cloud functionality and Firestore security rules.

## Features

- Modern TypeScript SPA architecture
- Fast development and build using Vite
- Firebase integration for backend and hosting
- Firestore security rules included
- Easily extensible for AI and automation use-cases

## Directory Structure

```
SomaAI/
├── src/                        # Application source code (TypeScript)
├── index.html                  # Main HTML entry point
├── package.json                # Node.js project manifest
├── package-lock.json           # NPM lockfile
├── tsconfig.json               # TypeScript config
├── vite.config.ts              # Vite configuration
├── firebase-applet-config.json # Firebase config for applet
├── firebase-blueprint.json     # Blueprint/config for Firebase setup
├── firestore.rules             # Firestore security rules
├── metadata.json               # Project/application metadata
├── .gitignore                  # Git ignores
└── README.md                   # This file
```

## Getting Started

These steps help you install dependencies and start the development server.

### 1. Install Node.js and npm

Make sure you have [Node.js](https://nodejs.org/) (v16+) and npm installed.

### 2. Install dependencies

In the `SomaAI` directory, run:

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```
This will start the Vite local development server. Open your browser at the given URL (typically http://localhost:5173).

### 4. Build for production

```bash
npm run build
```
The static files will be output to `dist/`.

### 5. Firebase Integration (Optional/Advanced)

- To configure Firebase hosting or Firestore, update `firebase-applet-config.json` and `firebase-blueprint.json`.
- Firestore security can be managed with `firestore.rules`.
- Deploy using the [Firebase CLI](https://firebase.google.com/docs/cli) if desired.

### 6. Project Metadata

- Extra configuration/meta is contained in `metadata.json`.

## Customization

- Edit code in the `src/` folder to extend or modify the app.
- Update `index.html` and `vite.config.ts` for custom HTML entry and advanced Vite settings.

## License

[MIT](../../LICENSE)

---

Feel free to contribute or suggest improvements!
