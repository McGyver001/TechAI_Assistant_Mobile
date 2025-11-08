Ford Tech Assist - Mobile update package

Contents:
- Mobile-optimized React + Vite app (Ford style)
- Live-updating inline SVG efficiency sparkline (no external chart libs)
- Login screen + main action buttons + performance screen + chat + admin demo
- assets/ford-logo.png placeholder and preview.png sample image

How to deploy:
1. Create a new GitHub repository.
2. Upload the contents of this folder (all files and folders) to the repo root.
3. In Vercel, import the repo. Framework: Vite. Build: npm run build. Output dir: dist.
Notes: This package avoids extra chart dependencies by using an inline SVG sparkline. You can replace the sparkline with chart.js later if desired.
