# DrainFix Plumbing & Jetting — GitHub Pages

This is a self-contained static website for DrainFix Plumbing & Jetting. It uses the supplied DrainFix logo and bundled project imagery, so it does not depend on WordPress, a database, a build server or external image hosting.

## Upload to GitHub Pages

Create a GitHub repository, upload the contents of this folder to the repository root, commit the files, then open **Settings → Pages**. Select **Deploy from a branch**, choose the `main` branch and the `/root` folder, and save. GitHub will publish `index.html` as the homepage.

The site includes `index.html`, `services.html`, `contact.html`, `404.html`, `styles.css`, `script.js`, local assets, `robots.txt` and `sitemap.xml`.

The contact form uses a `mailto:` fallback because GitHub Pages is static. Phone and WhatsApp buttons work directly on mobile devices. For form submissions without opening the visitor’s email app, connect the form to a service such as Formspree or Netlify Forms after publishing.

The canonical and sitemap URLs currently point to the existing DrainFix domain. If the GitHub Pages address is intended to be the primary public domain, update the canonical URLs and sitemap host after the custom domain is connected.
