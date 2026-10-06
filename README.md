# Muscle Anatomy Quiz — Supabase version

## Supabase project
The app is configured for the Supabase project ref `hlyzzonrcaklwfsibuaf`.

## Important
In `index.html`, replace:
`PASTE_YOUR_SUPABASE_PUBLISHABLE_KEY_HERE`
with the project's **publishable key** from Supabase Dashboard → Project Settings → API.

Never put the `service_role`/secret key in this HTML file.

## Database
The database schema and seed exercises are already in Supabase. The app reads exercises and pass mark from Supabase and saves authenticated quiz attempts.

## Admin
Create/sign in as a user, then set that user's `profiles.is_admin = true` in Supabase. The admin panel can then change the pass mark and add/delete exercises.

## GitHub Pages
Upload `index.html` to your repository and enable GitHub Pages. The CDN dependency is loaded by the browser.
