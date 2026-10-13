# CV

Personal LaTeX résumé — mostly so **Git** is the source of truth instead of a stray file in `Documents/` I keep losing or duplicating with twelve “final” names.

Based on the **ETH juniors** template (MIT), which in turn nods to [sb2nov/resume](https://github.com/sb2nov/resume).

**Install dependencies (Ubuntu/Debian):**

```bash
apt-get install texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra -y
```

**Build:** from the repo root, `pdflatex cv.tex` → `cv.pdf` next to `cv.tex`. Run it twice if something looks off after the first pass.
