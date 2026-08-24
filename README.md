# Priscilla Baiya — Portfolio

Static site for selected work. No build step, no framework — semantic HTML and a single stylesheet.

The first case study covers an MSc dissertation project on **synthetic facial age estimation**: generating identities with Stable Diffusion, aging them with a modified [AgeTransGAN](https://github.com/priscilla254/AgeTransGAN_myedit), and using the resulting set to train and evaluate age estimators.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Structure

```
├── index.html
├── case-studies/
│   └── synthetic-age-estimation/
│       └── index.html
├── assets/
│   ├── css/style.css
│   └── images/          ← dissertation figures
└── README.md
```

Drop charts into `assets/images/` and point the figure placeholders on the case study page at those files.

## Deploy

The folder is ready for [Vercel](https://vercel.com), Netlify, or GitHub Pages. Nested `index.html` files already map to clean URLs (`/`, `/case-studies/synthetic-age-estimation/`). Custom `vercel.json` routing is not required.
