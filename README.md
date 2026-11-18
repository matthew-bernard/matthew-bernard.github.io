# MA Thesis Notes in Statistics and Data Science

Research notes, code, and draft chapters for my MA thesis in Statistics and Data Science at UC Berkeley, advised by Professor Steven N. Evans.

## Live Site
Visit the live site here: [https://matthew-bernard.github.io/](https://matthew-bernard.github.io/)

## Notes & Chapters (Chronological Order)

- **[Spectrum of the Top-to-Random Chain on Two-Coloured Words](./2026-11-10-trs/index.html)** (November 10, 2026)  
  *A note based on discussions with Professor Steven N. Evans, analyzing the spectral properties, diagonalization, and multiplicities of the chain.*
- **[Spectral Degeneracies of a Top-to-Random Shuffle on Balanced Binary Words](./2026-11-03-trs/index.html)** (November 3, 2026)  
  *A note based on discussions with Professor Steven N. Evans, covering initial explorations and investigations into top-to-random shuffles on balanced binary words.*

## Repository Structure

- `index.qmd` / `index.html`: Main landing page for the site.
- `2026-11-10-trs/`: Folder containing the November 10 note, PDF, source code, and rendered HTML.
- `2026-11-03-trs/`: Folder containing the November 3 note, PDF, figures, and rendered HTML.

## Build Requirements

The site is built using [Quarto](https://quarto.org/) and Python (with `numpy`, `networkx`, `matplotlib`). To re-render the site locally, run:

```bash
quarto render
