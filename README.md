# Mithil Samudrala — Product Manager Portfolio

Personal portfolio website for Mithil Samudrala, Product Manager.

## Deploy

- **GitHub Pages**: Push to `main` branch, enable Pages in repo settings → Deploy from branch.
- **Netlify/Vercel**: Connect repo, no build step required (static HTML).

## Structure

```
├── index.html    # Main portfolio page
├── logo.png      # SNM logo (used in hero photo)
└── README.md
```

## Customization

Edit content directly in `index.html`:
- **Experience / Education / Certifications / Skills**: `TABS` array (line ~150)
- **Cover letter**: `LETTER` array (line ~195)
- **Built products**: `BUILT` array (line ~203)
- **Preferences**: `PREFS` array (line ~210)

## Local preview

Open `index.html` in a browser, or serve locally:

```bash
npx serve .
# or
python -m http.server 8000
```