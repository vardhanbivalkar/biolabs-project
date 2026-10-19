# Biolabs Biotech Readiness Quiz

A fast, browser-based assessment for researchers, PhD students and scientists who want to know how close their idea is to becoming a real biotech business.

## What it does

Users answer 16 questions across 4 scored dimensions and receive a personalised readiness profile with a score, dimension breakdown, their biggest strength and a concrete next step.

## Dimensions scored

| Dimension | What it measures | Max pts |
|---|---|---|
| 🎯 Market Need | Is there a real problem and a person who has it? | 9 |
| 🧫 Scientific Evidence | How solid and validated is the science? | 9 |
| 🗺️ Business Groundwork | IP ownership, costs, business model thinking | 9 |
| 🔥 Founder Drive | Motivation and bandwidth to build | 9 |

**Total: 36 points**

## Readiness profiles

| Score | Profile |
|---|---|
| 0–8 | The Curious Explorer |
| 9–18 | The Problem Spotter |
| 19–27 | The Proof Builder |
| 28–36 | The Founder in Waiting |

## Tech

- Single HTML file — no framework, no backend, no build step
- All scoring runs in the browser; no data is stored or transmitted
- Animated canvas background with DNA helices, cell membranes, molecule networks, microscope scan rings and pipette ripples
- Deployable to Netlify Drop, GitHub Pages or Cloudflare Pages in under a minute

## Run locally

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080/index.html](http://localhost:8080/index.html).

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to Settings > Pages
3. Set source to `main` branch, `/ (root)`
4. Your quiz will be live at `https://<username>.github.io/<repo-name>/`

## Structure

```
index.html   # entire app — HTML, CSS and JS in one file
README.md
```
