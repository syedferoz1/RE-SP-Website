# Deployment Guide - RE-SP-Website

This project is a static site (HTML/CSS/JS) and can be deployed on Vercel, Netlify or any static hosting.

Recommended (Vercel):
1. Create a Vercel account and connect your GitHub repository.
2. Set the Root Directory to the repository root.
3. If you generate production CSS/assets, set Build Command and Output Directory accordingly.
4. Add environment variables from `.env.example` into the Vercel project settings.

Serving static files:
- If you keep plain HTML/CSS/JS, Vercel will serve the files without a build step.
- To enable serverless lead capture, add a `api/` serverless function and set `LEADS_API_URL` accordingly.

Cache & headers:
- Add `vercel.json` with cache headers for static assets; example provided in repo.

Security:
- Ensure `CRM_API_KEY` and other secrets are configured in Vercel Dashboard (do not commit secrets to git).

Testing deployment:
1. Deploy preview from Vercel.
2. Test form submissions, WhatsApp links, and brochure downloads.
3. Run Lighthouse on the deployed preview and iterate on performance.

Rollback:
- Vercel keeps previous deployments; use the dashboard to roll back if needed.
