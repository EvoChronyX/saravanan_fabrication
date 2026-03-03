# S. Saravanan Engineering Works — Website

Professional website for **S. Saravanan Engineering Works**, an IBR-certified welding and fabrication contracting firm with 25+ years of industrial engineering experience.

## Tech Stack

- **HTML5** — Semantic, accessible markup
- **CSS3** — Custom properties, Grid, Flexbox, responsive design
- **Vanilla JavaScript** — Scroll animations, counters, mobile navigation
- **Font Awesome 6** — Icons
- **Google Fonts** — Inter + Space Grotesk

## Local Preview

```bash
npx serve .
```

Then open [http://localhost:3000](http://localhost:3000)

## Deploy to Vercel

### Option 1: Vercel CLI

```bash
npm i -g vercel
vercel
```

### Option 2: GitHub + Vercel Dashboard

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com) → **New Project**
3. Import the GitHub repo
4. Framework Preset: **Other**
5. Click **Deploy**

The site will be live at your Vercel URL within seconds.

## Project Structure

```
├── index.html      # Main HTML page
├── styles.css      # All styles
├── script.js       # Interactive features
├── vercel.json     # Vercel deployment config
├── package.json    # Project metadata
└── README.md       # This file
```

## Customization

- **Contact details**: Update phone number and email in `index.html` (search for `tel:` and `mailto:`)
- **Colors**: Modify CSS variables in `:root` at the top of `styles.css`
- **Content**: All text content is in `index.html`

---

&copy; S. Saravanan Engineering Works
