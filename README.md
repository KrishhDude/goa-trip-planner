# Goa, by train

A small static trip-options page for comparing four November weekends and one December weekend from Ernakulam to Madgaon. The site uses plain HTML, CSS and JavaScript, so it has no build step or runtime dependencies.

## Preview locally

Open `index.html` in a browser, or use the VS Code Live Preview extension if you prefer a local server.

## Publish with GitHub Pages

The included GitHub Actions workflow publishes the site whenever you push to `main`.

1. Create a **public** repository on GitHub. Do not initialize it with a README, license, or `.gitignore`.
2. In the repository, open **Settings → Pages** and set the build source to **GitHub Actions**.
3. In this folder, open a terminal and run the following commands, replacing `YOUR-USERNAME` and `YOUR-REPOSITORY` with your GitHub details:

	```powershell
	git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
	git add index.html README.md "Weekend 1.md" .github/workflows/pages.yml
	git commit -m "Add Goa trip options site"
	git push -u origin main
	```

4. In the repository, open **Actions** and wait for the Pages deployment to finish.
5. Share `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/` with your group.

No package installation or build command is needed. The public repository will also make the source notes in `Weekend 1.md` visible.

## Updating trip options

Edit the train details in `index.html`. Dates and availability are shown as provided in `Weekend 1.md`; check current schedules, fares and seat status before booking.
