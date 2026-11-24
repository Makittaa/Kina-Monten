# Kina Monten

An English-language offline maze puzzle game. Arrow keys / WASD or on-screen buttons. Collect all cheese and reach the exit.

## GitHub Pages
Create a public repository named `kina-monten`. Upload all files and folders from this directory to the repository root, including `.nojekyll`. In Settings > Pages, choose Deploy from a branch, main, / (root), Save. Open the published HTTPS URL.

## PWA
Open the published URL in Edge or Chrome and use Install game or the browser install menu. Visit once online before testing offline. For local testing run `python -m http.server 8000` in this directory and visit http://localhost:8000.

## Microsoft Store
Reserve Kina Monten in Partner Center if available. Enter the published HTTPS URL at https://www.pwabuilder.com/ and choose the Windows package. Use the identity and publisher values from Partner Center. Submit the generated Store upload package and provide screenshots and the published privacy.html URL. Certification is not guaranteed.

## Updates
Increment CACHE in sw.js when changing game files. No build dependencies.
