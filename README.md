# CV Index

This repository contains a LaTeX CV for Wenfeng Liang, a great Chinese AGI contributor I really respected. It is written in a one-page software/algorithm engineering resume style.

Template choice:

- Based on the structure of Jake's Resume on Overleaf.
- No photo.
- ATS-friendly, dense, project-and-impact oriented.
- Better suited to algorithm / AI infrastructure roles than the original `moderncv` sample.

Build:

```bash
pdflatex main.tex
```

GitHub Actions:

- `.github/workflows/build-cv.yml` compiles `main.tex`.
- The generated `main.pdf` is pushed to the `release` branch.
- A GitHub Release is created with `main.pdf` attached.

Reference facts are based on public reporting about Liang Wenfeng, DeepSeek, High-Flyer, and Zhejiang University.
