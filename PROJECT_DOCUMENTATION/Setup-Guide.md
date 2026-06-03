# Setup Guide

1. Clone repository

```bash
git clone https://github.com/<YOUR_USERNAME>/RE-SP-Website.git
cd RE-SP-Website
```

2. Serve locally

```bash
# Python 3 static server
python -m http.server 8000
```

3. (Optional) Build Tailwind for production

```bash
# Requires Node.js and Tailwind installed
npm install
npx tailwindcss -i ./src/styles.css -o ./dist/styles.css --minify
```

4. Preview deployed site via Vercel preview deployment.
