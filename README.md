# Momin Bukhari — Personal Portfolio

A personal portfolio website for **Syed Abdul Momin Bukhari** (Reg. No. 501993, SE 15 A), built as part of Web Engineering Lab 3.

## Live Demo

> Deploy via GitHub Pages and paste the URL here:
> `https://momin-bukhari.github.io/Portfolio-extend/`

## Project Structure

```
Portfolio-extend/
├── index.html          ← Entry point (redirects to home.html)
├── home.html           ← Landing / About page
├── hobbies.html        ← Hobbies & Interests
├── skills.html         ← Technical & Soft Skills
├── gallery.html        ← Image Gallery (7 photos, float layout)
├── contact.html        ← Contact form & details
├── css/
│   └── style.css       ← Single external stylesheet (all pages)
├── images/
│   ├── photo1.jpg      ← Profile avatar
│   ├── photo2.jpg      ← Tennis
│   ├── photo3.jpg      ← Table Tennis
│   ├── photo4.jpg      ← Cricket
│   ├── photo5.jpg      ← Campus
│   ├── photo6.jpg      ← Coding setup
│   ├── photo7.jpg      ← Philosophy / reading
│   └── photo8.jpg      ← Computer lab
└── README.md
```

## Key Features

- **External CSS** — all styling lives in `css/style.css`; zero inline styles.
- **Float & Clear layouts** — nav links, hero photo, about cards, skill pills, gallery grid, hobby cards, and contact columns all use CSS `float` and `clear`.
- **Horizontal navigation** — `<ul>` items are `float: left` inside a `float: right` nav list.
- **Image gallery** — 7 images arranged with float, including wide (2/3) and narrow (1/3) items; CSS-only lightbox.
- **No JavaScript** — fully functional without any scripts.
- **No CSS frameworks** — pure vanilla CSS only.

## Technologies

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (external stylesheet) |
| Fonts | Google Fonts (IM Fell English, Courier Prime) |
| Version Control | Git / GitHub |
| Hosting | GitHub Pages |

## Deployment (GitHub Pages)

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Set **Source** to `main` branch, `/ (root)` folder.
4. Save — GitHub will publish at `https://<username>.github.io/<repo>/`.

## Author

**Syed Abdul Momin Bukhari**  
Registration No. 501993 · Section SE 15 A  
Software Engineering, SEECS — NUST  
Email: sbukhari.bese24seecs@seecs.edu.pk
