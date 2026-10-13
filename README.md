# Slides

Talk slides, built with [reveal.js](https://revealjs.com/) 4.1.3.

## Deep Learning applied in Genetics (`phd_project/`)

PhD project talk, October 2021.

- PhD candidate: Matthieu de Hemptinne
- Promotor: Danielle Posthuma; second promotor: Tom Heskes

Topic: how deep learning can improve on genome-wide association studies (GWAS)
and polygenic risk scores (PRS). The talk introduces an autoencoder-based approach
that clusters individuals by genotype, estimates allele frequencies per population
to correct for population stratification, uses autoencoders to find linkage
disequilibrium, and combines both into a final model with SNP clustering. It
covers the main challenges (population stratification, linkage disequilibrium,
the curse of dimensionality) and results on three generated datasets.

## Viewing the deck

Serve the repository root with any static file server and open the deck:

```bash
npx serve .
# then open http://localhost:3000/phd_project/
```

To export a PDF, open the deck with `?print-pdf` appended to the URL
(e.g. `http://localhost:3000/phd_project/?print-pdf`) and print to PDF from
Chrome or Chromium.
