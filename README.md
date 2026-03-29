# DISC Personality Types

A DISC personality assessment survey built with Hugo.

**Live site:** https://disc-personality-types.ibrohim-syarif.workers.dev/

## What is DISC?

DISC is a behavior assessment model based on four personality traits:

| Type | Name | Description |
|------|------|-------------|
| **D** | Dominance | Direct, results-oriented, and decisive |
| **I** | Influence | Enthusiastic, optimistic, and collaborative |
| **S** | Steadiness | Patient, reliable, and supportive |
| **C** | Conscientiousness | Analytical, detail-oriented, and careful |

Everyone has a mix of all four traits. This survey identifies which types are most and least dominant in your behavior.

## How It Works

1. Answer each question by selecting which word **most** and **least** describes you
2. Navigate through all questions using the Next/Back buttons
3. Submit to see your dominant DISC personality type

## Project Structure

```
content/
  question/   # Survey question page
  result/     # Result display page
data/         # Question data
layouts/
  question/   # Question page template with survey logic
  result/     # Result page template
assets/       # CSS and JS assets
```

## Getting Started

```bash
hugo server
```

Open [http://localhost:1313](http://localhost:1313) in your browser.

## Built With

- [Hugo](https://gohugo.io/) — static site generator
