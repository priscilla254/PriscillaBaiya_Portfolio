# Priscilla Baiya — Portfolio

Static site for selected work. No build step, no framework — semantic HTML and shared stylesheets.

Four case studies:

- **RAG Construction Assistant** — a cited Q&A assistant over UK building regulations and HSE site safety guidance, with hybrid retrieval and Recall@5 of 0.90 on a 20-question labelled eval.
- **Synthetic facial age estimation** — an MSc dissertation: a three-stage pipeline (SDXL → AgeTransGAN → CodeFormer) for a demographically balanced dataset, with a fairness evaluation and a follow-up comparison of text-to-image models.
- **Applied AI for Construction costs** — a placement-year research proposal and proof of concept: a SQL Server star-schema warehouse behind a guarded natural-language SQL assistant, Power BI-ready reporting views, and automated report drafting.
- **Berlin S-Bahn Delay Prediction** — a leakage-safe LightGBM classifier on a synthetic transit dataset, with temporal cross-validation, sliced error analysis, and TreeSHAP explanations, shipped with CI, Docker, and a batch-scoring entry point.

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
│   ├── construction-cost-benchmarking/
│   │   └── index.html
│   └── sbahn-delay-prediction/
│       └── index.html
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── case-study.css
│   └── images/
└── README.md
```
