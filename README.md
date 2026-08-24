# Priscilla Baiya — Portfolio

Static site for selected work. No build step, no framework — semantic HTML and a single stylesheet.

The first case study covers an MSc dissertation on **synthetic facial age estimation**: a three-stage pipeline (SDXL → AgeTransGAN → CodeFormer) for a demographically balanced dataset, with a fairness and bias evaluation and a follow-up comparison of text-to-image models.

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
│   ├── css/
│   │   ├── style.css
│   │   └── case-study.css
│   └── images/
└── README.md
```

Optional charts and figures can go in `assets/images/`.

## Deploy

The folder is ready for [Vercel](https://vercel.com), Netlify, or GitHub Pages. Nested `index.html` files already map to clean URLs (`/`, `/case-studies/synthetic-age-estimation/`). Custom `vercel.json` routing is not required.
