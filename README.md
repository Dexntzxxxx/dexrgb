# Ghost Atlas

A small, black-and-neon-green place explorer with a harmless terminal look.

## What it does

- **Random IP** picks a place from a curated worldwide atlas. It does not inspect or resolve anyone's real IP address.
- Each generated place is automatically saved to the browser's local archive.
- Search archived drops, open a saved place, remove entries, or export the archive as JSON.
- Copy coordinates or share a place link. The map button opens that coordinate in Google Maps.
- See the place's region, elevation, local time, and a short field note.

Archive data stays in the current browser. It is not uploaded to a server and will not sync across devices. Export a JSON backup before clearing browser data.

## Publish with GitHub Pages

1. Merge this branch into `main`.
2. In the repository, open **Settings → Pages** and set the publishing source to **GitHub Actions**.
3. The workflow in `.github/workflows/deploy-pages.yml` publishes the site after a push to `main`. The deployed link appears in the repository's **Actions** workflow run.

The app uses Google Maps URLs to open selected coordinates, so it does not need an API key. The map preview is a lightweight stylized world grid drawn by the page itself.

