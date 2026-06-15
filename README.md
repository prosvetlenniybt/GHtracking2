[README.md](https://github.com/user-attachments/files/28967658/README.md)
# Experiment Quest

Gamified project and experiment tracker for managing product launches, test rollouts, analysis, presentations, and cleanup tasks.

## Features

- Project cards with launch readiness
- Required and optional task stages
- LocalStorage persistence
- JSONBin.io cloud sync
- XP-style progress
- Owner filters
- Export to JSON
- Reset saved data
- Responsive UI

## Tech stack

- React
- TypeScript
- Vite
- CSS

## Run locally

Install dependencies and start the dev server with your preferred package manager.

```bash
npm install
npm run dev
```

## JSONBin sync

The app works offline with LocalStorage by default. To sync between browsers/devices:

1. Create a JSONBin.io account.
2. Copy your X-Master-Key from JSONBin.
3. Open the app and paste the API key into the Cloud sync panel.
4. Click `+ Создать bin` to create a private bin automatically.
5. Use `Сохранить в JSONBin` to push current tracker data to the bin.
6. Use `Обновить из JSONBin` to load the latest data from the bin.

The Bin ID and API key are saved in this browser's LocalStorage. Do not publish your real API key in GitHub code or screenshots.

## Notes

This is an independent gamified project tracker prototype. It does not use Duolingo assets, branding, characters, or proprietary UI elements.
