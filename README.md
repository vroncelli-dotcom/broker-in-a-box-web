# Broker in a Box — Launch Kit Site

Weekly Heartbeat-styled internal hub for Broker in a Box.
Single-file React 18 + Babel Standalone (Orbit stack) — no build step.

## Deploy to Vercel
1. Drag this folder into the Vercel dashboard (Add New → Project → deploy folder),
   or from the CLI: `vercel --prod` inside this folder.
2. No framework preset needed — it's a static site. `index.html` is the entry.

## Before it goes live
- Set `APP_URL` at the top of the script in `index.html` to the BIB app deployment URL.
- Verify the placeholder figures (150–275 bps, $8–15K startup, $30M example math)
  against numbers cleared for internal use.
