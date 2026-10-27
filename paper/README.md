# Research Paper

This directory contains the final research paper and LaTeX source files for our mathematical modeling project on the evolution of cooperation and aggression in finite populations using the Moran process.

## Files

- **`MathModeling_Evolutionary_Dynamics_Cooperation_Paper`** — Final compiled research paper.
- **`main.tex`** — LaTeX source code for the paper, including mathematical formulations, methodology, and results.
- **`references.bib`** — BibTeX bibliography containing the references cited in the paper.

## Compiling the Paper

To compile the paper locally:

1. Ensure that a LaTeX distribution and BibTeX are installed.
2. Keep `main.tex` and `references.bib` in the `paper/` directory.
3. Ensure the required figures are available in the repository's `figures/` directory.
4. From the `paper/` directory, run:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

The compiled document will be generated as `main.pdf`.

## Notes

The Python simulation code, generated figures, and numerical results used in the paper are available in the corresponding `src/`, `figures/`, and `results/` directories.
