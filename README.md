# LP Agriculture

Landing page project for agriculture-related campaigns.

## Local Preview

Open `index.html` directly in a browser, or serve the repository as static files.

## Deployment

### CI validation

- `.github/workflows/ci.yml` verifies static HTML structure and validates `vercel.json`.

### Vercel

- `vercel.json` configures static output and SPA-friendly rewrites to `index.html`.
- Import the repository in Vercel and deploy from the default branch.

## Environment Variables

- No required runtime environment variables for the current static site.
- If future integrations are added, manage secrets in Vercel and keep `.env.example` updated.
