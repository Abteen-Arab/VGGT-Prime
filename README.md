# VGGT-Prime

Local project page for **VGGT-Prime: Compute-Adaptive Mixture-of-Heads for Efficient Visual Geometry Transformers** by Abteen Arab, Guile Wu, Chengjie Huang, and Dongfeng Bai.

## Preview

Open `index.html` directly, or run this command from this folder:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then visit <http://127.0.0.1:8000>. No installation or build step is needed. The page is static HTML and CSS, with local Bulma styles and optional Google Fonts. All figures and tables work without JavaScript or external services.

This folder is ready for GitHub Pages; `.nojekyll` is retained and all local asset URLs are relative. Nothing has been published.

## Content and sources

The supplied `VGGT_Prime_arxiv__Execute_` manuscript is the source of the authors, affiliations, abstract, figures, and results.

- `index.html`: page content and accessible HTML tables.
- `static/css/index.css`: responsive layout and plum theme, following the VGGT-Ω project page.
- `static/images/`: five unchanged manuscript figures, renamed for web-friendly URLs, plus the page favicon.

| Website figure | Manuscript source |
| --- | --- |
| `main-figure.png` | `Figures/Main_Figure.png` |
| `head-saliency.png` | `Figures/Analysis_1.png` |
| `attention-patterns.png` | `Figures/Analysis_2.png` |
| `architecture.png` | `Figures/Model Architecture-2.png` |
| `token-merging.png` | `Figures/ToMe Experiment.png` |

Benchmark data comes from `Table/Point_Cloud_all.tex`; backbone data comes from `Table/Generalization.tex`. Speedups in the HTML tables are ratios of reported runtimes, rounded to two decimals. The scaling figure's annotated speedups retain their original one-decimal precision. The abstract preserves its original rounded “up to 14×” statement; the scaling section reports 13.8×.

CD is the only reconstruction-quality metric in the result tables. The saliency-analysis figure includes its original pose-performance ablation. The teaser's backbone plot is ScanNet-500, while the backbone table is sparse 7-Scenes.

## Release links

Paper is intentionally disabled and labeled **Coming soon**. The Code button is omitted. When the paper URL is available, replace the disabled resource `<button>` with an `<a>` using the same classes and a verified `href`; remove `disabled`, `aria-disabled`, and the Coming soon status. No paper ID, venue, publication date, author homepage, or canonical project URL has been invented.

## Attribution

Built from the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), adapted from [Nerfies](https://nerfies.github.io/). Visual direction follows [VGGT-Ω](https://vggt-omega.github.io/).

The website template is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Manuscript figures remain supplied research assets.
