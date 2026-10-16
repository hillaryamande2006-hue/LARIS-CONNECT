# LARIS Connect — fresh prototype

A fresh front-end prototype for the Department of Library, Archival and Information Studies, University of Ibadan.

## Features included
- Overview dashboard
- Announcements with search; demo admins can add and remove items
- Event centre; demo admins can add and remove events
- Resource library with search and level filters
- Picture archive placeholder
- Feedback form and demo admin responses
- Local demo student profile
- Responsive mobile/desktop interface

## Run the app
You need Node.js 18 or newer. In this project folder run:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. To make a production build, run `npm run build`; the generated site is in `dist/`.

## Cloudflare Pages test
Upload the project to GitHub, then connect the repository to Cloudflare Pages. Use build command `npm run build` and output folder `dist`. No environment variables are needed for this demo.

## Important: prototype only
- All content is stored in the current browser's localStorage. It does not sync between students/devices.
- Demo profile is not real authentication or email verification.
- Admin passcode is intentionally visible in the source and is NOT secure. Demo passcode: `LARIS-DEMO-ADMIN`. Never use this for a live app.
- Actual file uploads/storage and secure downloads are not connected.
- Do not enter sensitive or real student data into this version.

Before production, connect a backend such as Supabase, configure authentication and database access rules, add role-based admin authorization, and implement secure file storage and approved photo uploads.
