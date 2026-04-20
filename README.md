# ✦ My Universe — Love Website

A beautiful, interactive starfield website built as a love letter for a long distance relationship. Each star in the sky holds a personal reason — hover to preview, click to read.

---

## Preview

- **Intro screen** — elegant animated title fades in on load
- **Interactive starfield** — 50 glowing stars scattered across a dark sky
- **Hover tooltip** — hovering a star reveals a short preview of the reason
- **Click modal** — clicking a star opens a full-screen card with the message
- **Shooting stars** — animated shooting stars fly across the sky periodically
- **Nebula glow** — soft color layers in the background for depth

---

## File Structure

```
love-universe.html   ← the entire website (single file, no dependencies)
README.md            ← this file
```

Everything is contained in a single `.html` file. No frameworks, no build tools, no installs needed.

---

## How to Customize

Open `love-universe.html` in any text editor and find the `reasons` array near the bottom of the `<script>` tag:

```js
const reasons = [
  "The way your face appears on my screen and suddenly the distance means nothing",
  "How you say goodnight across time zones just so I don't sleep alone",
  // ... edit any of the 50 reasons here
];
```

You can also edit the intro text in the HTML:

```html
<p class="intro-eyebrow">For you, always</p>
<h1 class="intro-title">My <em>Universe</em></h1>
<p class="intro-sub">Every star holds a reason I love you</p>
```

---

## Deploying (Free Hosting)

### Option 1 — Netlify (Recommended, easiest)

1. Go to [netlify.com](https://netlify.com) and sign up for free
2. Click **"Add new site"** → **"Deploy manually"**
3. Drag and drop `love-universe.html` onto the deploy area
4. Your site goes live instantly at a URL like `https://sparkly-rose-123.netlify.app`
5. You can set a custom subdomain (e.g. `my-universe.netlify.app`) in site settings

### Option 2 — Vercel

1. Go to [vercel.com](https://vercel.com) and sign up for free
2. Install the Vercel CLI: `npm install -g vercel`
3. In your project folder, run: `vercel`
4. Follow the prompts — your site will be live in seconds

### Option 3 — GitHub Pages

1. Create a free account at [github.com](https://github.com)
2. Create a new repository
3. Upload `love-universe.html` and rename it to `index.html`
4. Go to **Settings → Pages** and set the source to the `main` branch
5. Your site will be live at `https://yourusername.github.io/reponame`

---

## Browser Support

Works in all modern browsers — Chrome, Firefox, Safari, Edge. Also works on mobile (tap a star to open it).

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 Canvas | Star rendering and animation |
| Vanilla JavaScript | Interactivity, hover & click events |
| CSS3 Animations | Intro screen, nebula, modal transitions |
| Google Fonts | `Cormorant Garamond` + `Cinzel` typefaces |

No libraries. No frameworks. No dependencies. Just one HTML file.

---

*Made with love. ✦*