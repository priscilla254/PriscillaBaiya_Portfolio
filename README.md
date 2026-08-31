# Priscilla Baiya — Portfolio

Static site for selected work. No build step, no framework — semantic HTML and shared stylesheets.

Three case studies:

- **RAG Construction Assistant** — a cited Q&A assistant over UK building regulations and HSE site safety guidance, with hybrid retrieval and Recall@5 of 0.90 on a 20-question labelled eval.
- **Synthetic facial age estimation** — an MSc dissertation: a three-stage pipeline (SDXL → AgeTransGAN → CodeFormer) for a demographically balanced dataset, with a fairness evaluation and a follow-up comparison of text-to-image models.
- **Applied AI for Construction costs** — a placement-year research proposal and proof of concept: a centralised cost database, Power BI dashboards, and a Groq-powered AI layer for querying and report drafting.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Structure

```
├── index.html
├── case-studies/
│   ├── rag-construction-assistant/
│   │   └── index.html
│   ├── synthetic-age-estimation/
│   │   └── index.html
│   └── construction-cost-benchmarking/
│       └── index.html
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── case-study.css
│   └── images/
└── README.md
```

## Deploy

The folder is ready for [Vercel](https://vercel.com), Netlify, or GitHub Pages. Nested `index.html` files already map to clean URLs (`/`, `/case-studies/rag-construction-assistant/`, `/case-studies/synthetic-age-estimation/`, `/case-studies/construction-cost-benchmarking/`). Custom `vercel.json` routing is not required.
