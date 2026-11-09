# TrackWise

A personal productivity assistant for managing tasks, priorities and daily progress.

## Run locally

Requirements: Node.js 18+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Production build

```bash
npm run build
npm run preview
```

## Deploy to Vercel

1. Push this project folder to its own GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Framework preset: **Vite**.
4. Build command: `npm run build`.
5. Output directory: `dist`.
6. Deploy.

No environment variables are required for the starter version.

## Notes

- This is a frontend demo. Event, lead and task data are stored in the browser's `localStorage`; they are not shared across devices or users.
- LeadFlow's n8n integrations are suggested extension points, not preconfigured automations.
- TrackWise's assistant uses simple local rules, not a hosted LLM.
- VisionGuard loads the COCO-SSD model in the browser and needs an internet connection on first load.
- Replace sample records and placeholder contact data before presenting the project publicly.
