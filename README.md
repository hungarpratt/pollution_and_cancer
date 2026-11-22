# Something in the Air

This is a project I'm working on for my INFO 664 class at Pratt Institute (Programming for Cultural Heritage). It's a data story about lung cancer and air pollution in U.S. counties, starting from my family's history in Pittsburgh.

**Read the story:** https://hungarpratt.github.io/pollution_and_cancer/

## The question I'm investigating

Do counties that had more fine-particle air pollution (PM2.5) around 2000 have higher lung cancer rates today, and how much of that pattern is explained by air pollution as opposed to smoking or other factors?

## Data

- **Lung cancer incidence, 2019–2023:** State Cancer Profiles (National Cancer Institute and CDC), age-adjusted new cases per 100,000, by county
- **PM2.5, 1999–2003:** CACES (Center for Air, Climate, and Energy Solutions), modeled annual averages by county
- **Smoking, 1999–2003:** IHME county smoking prevalence estimates, 1996–2012
- **Maps:** U.S. Census Bureau 2020 cartographic boundary files for counties and states

## What's in this repo

| Folder or file | What it is |
| --- | --- |
| `notebook/analysis.ipynb` | All the data cleaning, analysis, and charts |
| `notebook/data/raw/` | The original downloaded data |
| `notebook/data/clean/` | Cleaned tables the notebook creates |
| `figures/` | Charts and photos used in the story |
| `index.qmd` | The story text (Quarto + Closeread) |
| `index.html` | The finished story that the website shows |

## How I update it

1. Make or change a chart in `notebook/analysis.ipynb`, saved to `figures/`
2. Add it to the story in `index.qmd`
3. Run `quarto render index.qmd` to rebuild `index.html`
4. Commit and push with GitHub Desktop
