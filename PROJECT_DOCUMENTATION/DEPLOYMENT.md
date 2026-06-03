# Deployment Notes

See root `DEPLOYMENT.md` for quick steps. Below are additional architecture notes for serverless lead capture and Vercel.

- To add serverless function for lead capture, create `api/leads.js` for Vercel functions.
- Securely read `CRM_API_KEY` and `LEADS_API_URL` from environment variables.
- Validate and sanitize incoming requests before forwarding to CRM.
- Add rate limiting or CAPTCHA verification to prevent spam.
