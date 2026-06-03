# RE-SP-Website

Project Title: RE-SP-Website

Project Description
-------------------
Premium real-estate lead-generation website for developers and channel partners. Includes a cinematic homepage, featured project listings, dynamic project detail templates, brochure download lead capture, site-visit booking, investment calculator, community explorer, WhatsApp assistant, and a demo lead management dashboard.

Features
--------
- Premium landing page and hero carousel
- Featured Projects showcase (4 projects)
- Reusable Project Details template with Gallery, Floor Plans, Amenities and Maps
- Brochure download modal with lead capture
- Site Visit booking modal
- Floating WhatsApp assistant
- Investment calculator
- Community explorer (schools, hospitals, metro, airport, malls)
- Demo Lead Management Dashboard

Technology Stack
----------------
- HTML5, CSS (Tailwind utilities), JavaScript
- Hosted as static site (Vercel recommended)

Installation
------------
1. Clone the repository:

```bash
git clone https://github.com/<YOUR_USERNAME>/RE-SP-Website.git
cd RE-SP-Website
```

2. Serve locally (simple static server):

```bash
# Python 3
python -m http.server 8000
```

Open `http://localhost:8000` in your browser.

Development Setup
-----------------
- Edit HTML/CSS/JS files directly in the workspace.
- For production Tailwind builds, install Node and Tailwind CLI and build a compiled CSS.

Environment Variables
---------------------
Create a `.env` file from `.env.example` and fill real values for:
- `LEADS_API_URL`
- `CRM_API_KEY`
- `GA_MEASUREMENT_ID`
- `WHATSAPP_NUMBER`

Folder Structure
----------------
```
index.html
project-details.html
dashboard.html
thank-you.html
pricing.html
assets/
	images/
	js/
	css/
PROJECT_DOCUMENTATION/
```

Deployment Instructions
-----------------------
1. Connect repository to Vercel (recommended)
2. Set environment variables in Vercel dashboard
3. Deploy (no build step required for static HTML), or add a build step if you compile Tailwind

Future Enhancements
-------------------
- Implement serverless lead capture (Vercel functions) to persist leads to a CRM
- Add authentication and production dashboard with role-based access
- Build production Tailwind CSS and convert images to WebP

Contact
-------
Owner / Maintainer: <your-name-placeholder>

See `DEPLOYMENT.md` and `CONTRIBUTING.md` for more details.
