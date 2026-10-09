SILLINK GROUP — THEME SWITCH FIX

WHAT CHANGED
- The LIGHT MODE / DARK MODE switch is inserted immediately before the About navigation item where that markup is identifiable.
- The switch is keyboard-accessible and updates its accessible label/state.
- The chosen theme is saved in localStorage so it persists on the same browser.
- Theme switch styling and behavior are included in styles.css and script.js.

DEPLOY TO VERCEL
1. Extract this ZIP.
2. Upload/replace the files in the ROOT of the GitHub repository connected to your Vercel project.
   Replace index.html, styles.css, and script.js. Keep sillink-logo.png in the same root if included.
   Do not upload the ZIP file itself as the website source.
3. Commit the changes to the branch configured as the Vercel Production Branch (commonly main).
4. In Vercel, open Project Settings > Git and confirm the correct GitHub repository and Production Branch are connected.
5. Make sure automatic deployments are enabled. A push to the Production Branch should start a new production deployment.
6. Open Deployments and wait for the latest deployment to show Ready. If it does not start, use Redeploy or reconnect the correct repository/branch.
7. Hard-refresh the website (Ctrl+Shift+R) or test in a private window to avoid stale browser cache.

IMPORTANT
This package cannot change your GitHub repository or Vercel project by itself. Automatic Vercel updates require the correct Git integration and a successful commit/push to the configured branch.
