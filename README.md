DataPulse B2B — Website
Verified B2B company & decision-maker data, data enrichment, verification, and research services for sales teams across global markets.
🌐 Live Site
Once deployed on Vercel, your live link will look like:
`https://your-project-name.vercel.app`
📁 Project Structure
```
.
└── index.html   # Single-page website (all sections + styling + logic included)
```
This is a single-page site — all sections (Services, Why Us, Pricing Calculator, Process, Privacy Policy, Terms, Opt-Out, Data Sourcing) live inside `index.html` and are linked via in-page anchors (e.g. `#services`, `#calculator`).
No separate CSS/JS files are needed — styling and icons are loaded via CDN:
Tailwind CSS (via CDN)
Lucide Icons (via CDN)
Google Fonts — Inter
🚀 Deploy on Vercel
Fork or clone this repo.
Go to vercel.com and sign in with GitHub.
Click Add New → Project, select this repository, and click Import.
No build settings needed (static HTML) — click Deploy.
Your site goes live in seconds at a `vercel.app` URL.
Every time you push a change to `index.html` on GitHub, Vercel will automatically redeploy the updated site.
✏️ Making Changes
Just edit `index.html` directly (locally or via GitHub's web editor), commit, and push. Vercel handles the rest.
📄 License
© DataPulse B2B. All rights reserved.
