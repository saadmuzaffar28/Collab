# CollabRev Solutions website

Single-page marketing site for CollabRev Solutions: dedicated FP&A, accounting and RCM teams for dental offices and DSOs, with Collab's AI-assisted dashboards.

Everything lives in `index.html`, including the styles, scripts and dashboard screenshots. There is no build step.

## Preview locally

Double-click `index.html` to open it in any browser.

## Make it live (Netlify, free)

1. Sign in at [netlify.com](https://www.netlify.com) with GitHub.
2. **Add new site → Import an existing project → GitHub**, then choose this repository.
3. Leave the build command empty and set the publish directory to `/`. Click **Deploy**.
4. Optional: under **Domain management**, add your own domain.

Every change pushed to this repository updates the live site automatically.

Vercel works the same way: import the repository, choose the "Other" framework preset, and deploy.

## Editing

- **Text:** open `index.html` on GitHub, click the pencil icon, edit the wording, then commit. The page content is plain HTML in the `<body>`.
- **Colors:** change the variables at the top of the `<style>` block (for example, `--navy` and `--blue-ink`).
- **Dashboard screenshots:** these are embedded as base64 images, so replacing one is easiest with help from a developer or Claude.

## Before going live

- **Contact form:** it currently only shows a thank-you message and doesn't send anything. Connect it to a form service (Netlify Forms, Formspree, or your CRM) so submissions reach you.
- **Contact details:** add a phone number, email and address if you want them shown in the top bar and footer.
- **Security claims:** confirm the wording in the FAQ and top bar (HIPAA-aware workflows, confidentiality agreements, secured workstations) matches your actual practices.
