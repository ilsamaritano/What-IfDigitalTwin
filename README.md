# Quantifying Resilience of Cyber-Physical Systems to Zero-Day Threats

Interactive website for the ESREL 2026 paper by **Fabrizio Baiardi** and **Vincenzo Sammartino**
(Dipartimento di Informatica, Università di Pisa).

A security twin-based *what-if* analysis framework that injects hypothetical zero-day
vulnerabilities into a digital twin of a cyber-physical system and measures resilience
degradation (MTTC, IS%) via Monte Carlo adversary simulation.

## Contents

- `index.html` — the site: fully self-contained (no build step, no external dependencies),
  with an interactive scenario explorer, result charts, and dark/light theme support.
- `paper.pdf` — the paper.

## Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. Repository **Settings → Pages → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. The site goes live at `https://<user>.github.io/<repo>/`.

To preview locally, just open `index.html` in a browser.
