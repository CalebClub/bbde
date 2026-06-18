# builtbyduke.de

Production-ready static multi-page website for deployment on Netlify.

## Tech Stack

- HTML5 (multi-page)
- CSS3 (single global stylesheet)
- Vanilla JavaScript (single global script)

## Project Structure

.
|-- 404.html
|-- index.html
|-- netlify.toml
|-- portfolio.html
|-- services.html
|-- staff.html
|-- style.css
|-- script.js
|-- .gitignore
`-- assets
	 |-- icons
	 |   |-- discord.svg
	 |   |-- email.svg
	 |   |-- github.svg
	 |   `-- globe.svg
	 `-- images
		  |-- background.jpg
		  `-- profile.jpg

## Run Locally

Because this is a static site, you can open `index.html` directly.

For a local server (recommended):

```bash
npx serve .
```

Then open the URL printed in your terminal.

## Deploy to Netlify

1. Push this repository to GitHub.
2. In Netlify, click "Add new site" -> "Import an existing project".
3. Select this repo.
4. Build command: leave empty.
5. Publish directory: `.`
6. Deploy.

`netlify.toml` is already included and production-ready for this static setup.

## Customize Content Quickly

1. Update display name and hero text:
	- `index.html`
2. Update social/contact links:
	- `index.html`
	- `services.html`
	- footer links on all pages
3. Update staff resume details:
	- `staff.html`
4. Update project cards:
	- `portfolio.html`
5. Update color/style system:
	- `style.css` CSS variables in `:root`

## Notes

- The small AI lock label text has been set to exactly: `password needed (CAI)`.
- The script keeps the passphrase check as `FISHERTHECAT` for the local demo widget.
- Your provided images are wired as:
  - `assets/images/profile.jpg`
  - `assets/images/background.jpg`
