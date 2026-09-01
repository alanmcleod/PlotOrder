# Plot Order — small version

This is the compact, framework-free version of Plot Order. It contains no dependencies and does not need a build step.

## Upload to GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `styles.css`, `app.js`, `manifest.webmanifest`, `README.md`, and the complete `icons` folder.
3. Open the repository's **Settings**.
4. Select **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose the `main` branch and `/ (root)`, then press **Save**.

GitHub will show the public address when publishing is complete.

## Saving

The app saves automatically in the current browser. Use **Export backup** to move or safeguard the data, and **Import backup** to restore it.

On a phone, use **+ New** beside the book selector to add a book. Use **Rename book** above the plot list to change the current book's title.

Deleting a plot point is deliberately placed at the bottom of its expanded notes and requires confirmation, reducing accidental deletion.

## Files

- `index.html` — page structure
- `styles.css` — appearance and phone layout
- `app.js` — all app behaviour
- `manifest.webmanifest` — installable web-app settings
- `icons/` — browser, iPhone and app icons

No Node.js, packages, compilation or server database is required.
