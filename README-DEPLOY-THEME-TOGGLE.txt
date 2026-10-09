SILLINK GROUP — THEME SWITCH FIXED SOURCE PACKAGE

Fixes included:
- Exactly one visible Light Mode / Dark Mode switch, immediately before About.
- One click handler only (the earlier duplicate handlers were removed).
- Theme preference persists in localStorage.
- Dark theme styling for the main sections, navigation, cards, contact form and footer.
- Responsive styling for desktop and mobile.

DEPLOYMENT
1. Upload/replace index.html, styles.css, and script.js in the ROOT of the GitHub repository actually connected to the inspiremepay.com Vercel project.
2. Keep sillink-logo.png and the other project files in the same root as before.
3. Commit and push to the branch set as Vercel's Production Branch.
4. In Vercel > Project Settings > Git, confirm the repository and production branch are correct and automatic deployments are enabled.
5. Wait for the newest deployment to show Ready, and ensure www.inspiremepay.com is assigned to that project.
6. Hard-refresh (Ctrl+Shift+R) or test in a private window.

This ZIP cannot publish itself to GitHub or change Vercel settings. Future Git pushes auto-deploy only if the correct repository/branch integration is configured.
