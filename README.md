# Seitenpraxis website

Complete static website export: HTML, CSS, JavaScript and image assets.
Source version: 65516d1525e05074cf88276ab8f2e77780047f03

## Upload to GitHub

1. Extract this ZIP on your computer.
2. Create an empty GitHub repository (a private repository is suitable for code storage).
3. Upload the extracted files and folders, preserving their structure. Upload the contents, not the ZIP itself.
4. Commit the upload. The root index.html, assets/ and all page folders must remain together.
5. Select the repository in Codex to continue editing the website.

No npm install or build command is needed.

## Preview locally

Run this command in the extracted folder with Python 3 installed:

    python -m http.server 8000

Open http://localhost:8000/ in your browser.
The ad landing page is /praxiswebsite/ and the contact page is /kontakt/.

## Hosting notes

Use a static host that serves the contents of this folder at the domain root.
Asset links start with /, so hosting under a subfolder needs path adjustments.
Uploading this export to GitHub does not synchronise or change the existing ChatGPT Sites website. Configure hosting/deployment separately if you want GitHub updates published automatically.

The enquiry forms open a prepared email in the visitor's email application; they do not send submissions through a backend service.

This export contains the website files, not Git history, hosting credentials, or the ChatGPT Sites deployment configuration.
