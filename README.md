# The Way I Work — Hang

A personal user manual built as a standalone HTML file.  
Designed to help colleagues understand how to work best with me.

## How to use

1. Open `index.html` in any browser — no server or install needed.
2. Add your banner image (see below).
3. Deploy to GitHub Pages to share a live link.

## Adding your personal banner

1. Place your banner image inside the `images/` folder
2. Rename it to `banner.png` (or `banner.jpg`)
3. If using `.jpg`, update the `src` in `index.html`:
   ```html
   <img src="images/banner.jpg" ... />
   ```
4. Recommended size: **1100 × 220px** — wider banners scale down automatically

If no image is found, a gradient placeholder is shown automatically.

## File structure

```
the-way-i-work/
├── index.html        ← the main file
├── images/
│   ├── banner.png    ← your personal banner goes here
│   └── README.txt    ← image guidance
└── README.md         ← this file
```

## Deploying to GitHub Pages

1. Push this folder to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your manual will be live at `https://yourusername.github.io/repo-name`
