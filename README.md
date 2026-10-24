# AI Security Workshop - GitHub Pages

This folder is a complete static website. No build step, Node.js, API key, database, or Sites service is required.

## Publish on GitHub Pages

1. Create a new GitHub repository, for example `AI-Security-Workshop`.
2. Upload the CONTENTS of this folder to the repository root. `index.html` must be directly in the root, alongside `styles.css`, `app.js`, `assets/`, and `.nojekyll`.
3. Commit the files to your `main` branch.
4. Open repository Settings > Pages. Under Build and deployment, choose Deploy from a branch, select `main` and `/(root)`, then Save.
5. When GitHub finishes deployment, open the URL shown in Pages settings. For your account and this example repository name it will be https://sanketshewalecybgit.github.io/AI-Security-Workshop/.

Use a new repository if you want to keep the existing MyProfile portfolio separate. Nothing here changes that repository automatically.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Preview locally

Open index.html in your browser, or run `python -m http.server 8000` from this folder and open http://localhost:8000.

## Edit later

- index.html: page copy, pricing, contact information, instructor section, FAQ.
- styles.css: fonts, colors, layout, glass finish, responsive styling.
- app.js: curricula, insight panels, programme selection, WhatsApp messages.
- assets/instructor.jpg: instructor photo.
- assets/fonts/: locally stored fonts and their licenses.

All rendering assets are local. External destinations remain intentional links: WhatsApp, email, LinkedIn, and the existing portfolio. Enquiry opens a prefilled WhatsApp chat; visitors send the message themselves. No payment or seat reservation is taken here.

Curriculum is displayed on-page only. No curriculum PDF downloads are included. No credentials, Git history, or private hosting metadata are included.
