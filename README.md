GTN Dining — Single-file prototype

This repository contains the GTN Dining HTML prototype (index.html) with added PWA manifest and service worker and demo auth/onboarding UI.

Files included:
- index.html
- manifest.json
- sw.js

Note: The original Downloads folder contains many other files (images, documents, installers). Those are intentionally excluded from version control by .gitignore to avoid leaking personal data.

To publish to GitHub and connect to Vercel:
1. Create a new repo on GitHub named `gtn-dining` (no README, no license).
2. On this machine run:

   git remote add origin git@github.com:YOUR_USERNAME/gtn-dining.git
   git branch -M main
   git push -u origin main

   (Or use the https remote: https://github.com/YOUR_USERNAME/gtn-dining.git)

3. In Vercel: Import project from GitHub and select this repository. Use the default settings (framework: Other) and deploy.

Security:
- Revoke any Vercel tokens you no longer need at https://vercel.com/account/tokens

