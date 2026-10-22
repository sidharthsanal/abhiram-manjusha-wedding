# Abhiram & Manjusha Wedding Reception Website

Complete static website with photos, animations, countdown, map link and calendar download. No installation, dependencies or build command required.

## Fastest: Netlify manual deploy
1. Extract this ZIP.
2. Sign in at https://app.netlify.com/drop
3. Drag the extracted Abhiram_Manjusha_Launch_Ready folder onto the drop area. The folder must contain index.html directly.
4. Netlify gives you a live URL. You can change the site name in Netlify.

## GitHub + automatic Netlify updates
1. Create a GitHub repository.
2. Upload the CONTENTS of this folder to the repository root: index.html, assets/, reception.ics, netlify.toml and the other included files. Do not upload the ZIP itself.
3. In Netlify, import an existing project from GitHub and select that repository.
4. Base directory: leave empty. Build command: leave empty. Publish directory: .
5. Deploy. Future pushes to the selected production branch trigger Netlify updates.

## Optional: host directly on GitHub Pages
1. Upload the files to the main branch with index.html at the repository root.
2. Open repository Settings > Pages.
3. Choose Deploy from a branch, then main and / (root), and save.
4. GitHub displays the website URL after publishing. Keep .nojekyll included.

## Edit
Open index.html in your editor or Google Antigravity. CSS and JavaScript are embedded in this file. Photos and background music are in assets/. Keep filenames and relative paths intact. The calendar event is reception.ics.

## Launch checks
After deployment, test on a phone: invitation opening, photo gallery, map button, calendar download and countdown. No RSVP collection or server is configured. This package has been checked for missing local HTML asset references; a live browser check is still needed.
