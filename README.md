# Our Adventures Together ❤️

A romantic travel keepsake website — a personal gift for Alon — featuring travel memories and trip summaries.

Built with pure HTML and CSS. No frameworks, no JavaScript. Ready to deploy on GitHub Pages.

## ✨ What's Inside

- **Home page** (`index.html`) — hero, trip cards, personal letter
- **Italy & Switzerland page** (`italy.html`) — full write-up of the May 2026 trip
- **Korea page** (`korea.html`) — full write-up of the Sep–Oct 2025 trip
- Photo galleries on each trip page with hover effects
- Fully responsive (desktop, tablet, mobile)

## 🗂️ Project Structure

```
our-adventures-together/
├── index.html       # Home
├── italy.html       # Italy & Switzerland trip
├── korea.html       # South Korea trip
├── styles.css       # Shared styles
├── images/          # Location-specific photos
│   ├── home-hero.jpg
│   ├── italy-hero.jpg, lake-garda.jpg, riva-del-garda.jpg, ...
│   ├── korea-hero.jpg, gyeongbokgung.jpg, bukchon.jpg, ...
│   └── CREDITS.md
├── README.md
└── .gitignore
```

All images are bundled locally — no external image dependencies. They're sourced from
[Unsplash](https://unsplash.com) (free license, see `images/CREDITS.md`).

## 🚀 How to Run Locally

Just double-click `index.html` and it will open in your browser. No build step needed.

## 🌐 Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `our-adventures-together`).
2. Upload all files from this folder.
3. In your repo, go to **Settings → Pages**.
4. Under **Source**, choose `main` branch and `/ (root)` folder.
5. Save — your site will be live at:
   `https://<your-username>.github.io/our-adventures-together/`

## 💡 How to Customize

- Edit text content directly in the `.html` files.
- Swap any photo by replacing the Unsplash URL with your own (or with a local file in an `images/` folder).
- Tweak colors in `styles.css` — all main colors live in the `:root` variables at the top.
- To add a new trip:
  1. Duplicate `italy.html` (or `korea.html`) and rename it (e.g. `japan.html`).
  2. Update the hero, content, and image URLs.
  3. Add a new card to the trips section in `index.html`.

---

Made with love ❤️
