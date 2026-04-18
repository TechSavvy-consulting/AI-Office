[README.txt](https://github.com/user-attachments/files/26855364/README.txt)
AI Office website bundle

Files included:
- index.html
- favicon.png
- assets/logo/*
- assets/sops/*

GitHub Pages setup:
1. Create or open your GitHub repo.
2. Upload index.html, favicon.png, and the entire assets folder to the repo root.
3. Delete README.md if GitHub is showing that instead of the site.
4. In GitHub: Settings > Pages.
5. Set Source to "Deploy from a branch".
6. Set Branch to "main" and Folder to "/ (root)".
7. Save. GitHub will publish the site and show the live URL on the Pages screen.

Formspree setup:
1. Create a Formspree account and create a new form.
2. Copy the endpoint shown in Formspree. It looks like: https://formspree.io/f/xxxxxxx
3. Open index.html and replace https://formspree.io/f/REPLACE_ME with your real endpoint.
4. Commit the updated index.html to GitHub.
5. Submit a test form from the live site and confirm the submission arrives in Formspree.

Notes:
- The logo shown in the website is inline SVG, so the site does not depend on an external logo path for the header.
- SOP download links point to assets/sops/*.pdf, so keep that folder structure when uploading.
