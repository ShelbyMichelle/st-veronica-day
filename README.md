# St Veronica Day — Standalone Site

A single-file website (HTML + Tailwind CDN + vanilla JS) ready for **GitHub Pages**.

## How to publish on GitHub Pages

1. Create a new GitHub repo (e.g. `st-veronica-day`).
2. Copy **`index.html`** from this folder into the root of that repo.
3. Create an `images/` folder next to it and drop your event photos in.
4. In the repo: **Settings → Pages → Branch: `main` / root → Save**.
5. Your site will be live at `https://<your-username>.github.io/st-veronica-day/`.

## How to customize

Open `index.html` and scroll to the big comment that says
**"EDIT THIS SECTION"**. You'll find three arrays:

- `PHOTOS` — image URLs + captions. Use local paths like `images/photo1.jpg`
  after you add photos to the `images/` folder.
- `VIDEOS` — YouTube embed URLs (`https://www.youtube.com/embed/VIDEO_ID`)
  or direct `.mp4` files.
- `MESSAGES` — quotes/testimonies with name and role.

Nothing else needs to change. Colors are sky-blue + white throughout, and
the layout is fully responsive.

## Tips

- **YouTube embed URL**: from a normal YouTube link
  `https://www.youtube.com/watch?v=ABC123`, the embed version is
  `https://www.youtube.com/embed/ABC123`.
- For best photo quality, use images ~1200px wide, JPG format.
- The site works offline once loaded, except the Tailwind CDN and fonts.
