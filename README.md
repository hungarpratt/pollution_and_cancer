# Something in the Air

This is a project I'm working on for my INFO 664 class at Pratt Institute (Programming for Cultural Heritage). It's a data story about the connection between lung cancer and air pollution in U.S. counties, prompted by my family's history in Pittsburgh and my parents' recent lung cancer diagnoses.

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
