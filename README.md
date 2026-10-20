# EduCloud School Portal — tested frontend + cloud-ready setup

## What was fixed
- Added the missing CSS, JavaScript and Supabase config files that the original HTML referenced.
- Added working demo login, navigation, responsive mobile menu and localStorage persistence.
- Added working Add/Delete flows for students, teachers, attendance, results, fees and notices.
- Added dashboard calculations and validation/escaping for displayed data.
- Cloud login is optional until Supabase credentials are configured.

## Run locally
Open `index.html` in a browser. Click **Use demo mode**. No server is required for demo mode.

## Deploy
Upload the whole folder to Vercel/Netlify/GitHub Pages. Keep `index.html`, `style.css`, `app.js`, `config.js` in the same folder.

## Enable real cloud login
1. Create a Supabase project.
2. Run `supabase-schema.sql` in Supabase SQL Editor.
3. Enable Email/Password authentication and create a user.
4. Put the Project URL and anon/public key in `config.js`.
5. Never put a Supabase service_role key in frontend code.

## Security warning
The sample RLS policies are development-level and allow authenticated users broad access. Before production use, replace them with role/owner-specific policies and test each role.
