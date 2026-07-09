# Algal Blooms in Lake Chapala: A Differential Equation Model

This research develops a **differential equation model** to study algal bloom dynamics in **Lake Chapala, Mexico**. The model captures how periodic pesticide application and government intervention influence algae population density over time by separating **growth** and **death** terms in a single ODE framework.

Using observed environmental data, the parameters of the model are calibrated to represent:
* pesticide application cycles (periodic schedule)
* maximum percent growth rate
* gradual decrease of bloom intensity

The model is solved analytically and analyzed to determine when the algae population exceeds the **odor threshold of 100 g/m²**, which can negatively affect drinking water quality for nearby communities.

**Supervisor:** Professor Cayce Fylling (Gettysburg College)

## Repository Structure

```
algal-bloom-de-model/
├── arxiv/                  # LaTeX project — source files
│   ├── main.tex
│   ├── biblio.bib
│   └── figures/
├── paper/                  # compiled PDF
├── project/overleaf.zip    # ready-to-go Overleaf upload
├── docs/                   # associated documents – contains observed environmental data
└── README.md
```

## Overleaf (recommended)

**Option A — use the ready-to-go zip**

1. Download [`project/overleaf.zip`](project/overleaf.zip)
2. [Overleaf](https://www.overleaf.com) → **New Project → Upload Project**
3. Upload the zip — it compiles `main.tex` automatically

**Option B — zip the folder yourself – (if you make any changes to the manuscript)**

1. Zip the contents of [`arxiv/`](arxiv/) (`main.tex`, `biblio.bib`, `figures/`)
2. Upload to Overleaf the same way

## Read the paper

Open [`paper/Algal-Blooms-A-DE-Model.pdf`](paper/Algal-Blooms-A-DE-Model.pdf).

## arXiv

TODO: *(Add after submission: `arXiv:XXXX.XXXXX`)*

## Authors

* **Soikat Saha**
* **Shruti D. Mishra**

## License

MIT License — see [LICENSE](LICENSE).

## Acknowledgments

* Research supervised by **Professor Cayce Fylling** (Gettysburg College)
* Environmental scenario data from Harwood (SIMIODE)
