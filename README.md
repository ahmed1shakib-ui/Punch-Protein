# Punch Protein

Static promotional landing page for Punch Protein, a peanut punch protein drink. Built with HTML, CSS, inline JavaScript, and PNG assets.

## Preview locally

The site is packaged in `Punch-Protein-Website-export.zip`. Download or clone this repository, then extract the ZIP. Inside `Punch-Protein-Website-export/`, open `index.html` in a browser. No package installation or build step is required.

Alternatively, with Python 3 installed, run from the repository root:

```sh
python3 -m zipfile -e Punch-Protein-Website-export.zip .
python3 -m http.server 8000 --bind 127.0.0.1 --directory Punch-Protein-Website-export
```

Visit <http://127.0.0.1:8000>. Stop the server with Ctrl+C.

## Editing and hosting

Edit `index.html` for content and form behavior, `styles.css` for styling, and `assets/` for images. A static host should serve the extracted folder with `index.html` at its document root. Google Fonts are loaded from the internet.

The waitlist forms are a front-end demo: submission is prevented, the form is reset, and a success message is shown. Emails are not saved or sent. Connect a backend or form service before using the page to collect signups. The Privacy Policy and Terms of Use labels are placeholders, not linked pages.

## License

No license file is included in the repository or site archive. Licensing terms for the code and bundled images have not been specified; the owner should confirm those rights and choose a license before reuse permissions are stated.
