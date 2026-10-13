FOUR SQUARES — Mobile Web App

WHAT'S INCLUDED
- index.html: the game
- manifest.webmanifest: installable app metadata
- service-worker.js: offline caching after the first load
- icon.svg: home-screen/browser icon

HOW TO PLAY
Tap any square to switch it ON or OFF. Each square works independently. Use Reset all to turn every square off.

HOW TO PUT IT ON YOUR PHONE
The app needs to be hosted at an HTTPS address before browsers can install it as a home-screen app. Opening index.html directly is fine for a quick local test, but install/offline features require hosting.

Simple hosting option: GitHub Pages
1. Sign in to GitHub and create a new public repository named four-squares.
2. Upload the four files from this folder to the repository's root.
3. Open the repository's Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch, select the main branch and /(root), then Save.
5. Wait for GitHub to publish the site. Its address will look like https://YOUR-USERNAME.github.io/four-squares/
6. Open that HTTPS address on your phone.
7. iPhone: Safari → Share → Add to Home Screen.
   Android: Chrome → menu (⋮) → Add to Home screen or Install app.

The app runs locally in the browser after it has been loaded and cached once. Hosting-provider screens and menu wording may change.
