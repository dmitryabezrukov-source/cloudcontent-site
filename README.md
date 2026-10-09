# CloudContent — corporate website

Responsive Russian-language corporate website for CloudContent, with solution tabs, product ecosystem, industry expertise and an email project brief.

## Deployment on Render

- Service type: Static Site
- Branch: `main`
- Build command: `echo 'Static site ready'`
- Publish directory: `dist`
- Auto-deploy: enabled

The repository includes `render.yaml` for Blueprint deployment. No build dependencies, environment variables or backend services are required.

The contact form prepares an email in the visitor's mail client. It does not store submissions or deliver them to a CRM.

## Files

- `dist/index.html`: page and Russian-language content
- `dist/style.css`: responsive layout and styling
- `dist/app.js`: solution tabs, mobile menu and email form
- `dist/assets/`: client logo assets

Visual browser QA remains to be completed.
