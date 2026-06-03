# Architecture Overview

This project is a static multi-page site with optional serverless extensions.

Components:
- Static HTML pages (`index.html`, `project-details.html`, `dashboard.html`, `thank-you.html`)
- Assets folder (`assets/images/`)
- Client-side JS for interactions and animations
- Optional serverless functions for lead capture (recommended to persist leads in CRM)

Design decisions:
- Keep the frontend simple and static for fast deployment and easy customization by developers.
- Use serverless endpoints only for form submissions / persistence to minimize infrastructure.
- Preserve the premium UI by using CSS glassmorphism and Tailwind utility classes.
