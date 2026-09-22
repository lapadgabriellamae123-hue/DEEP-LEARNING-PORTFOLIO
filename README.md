# ds-portfolio

My personal Data Science portfolio for DS Elective 4, built with [Jupyter Book](https://jupyterbook.org/) and published through GitHub Pages.

**Live site:** https://lapadgabriellamae123-hue.github.io/DEEP-LEARNING-PORTFOLIO/

## Contents

| Lab | Topic |
|---|---|
| Lab 2 | Forward pass through a small neural network + error computation |
| Lab 3 | Forward and backward propagation (manual backprop) |
| Lab 4 | Linear regression trained end-to-end in PyTorch |
| Lab 5 | PyTorch tensor fundamentals |
| Lab 6 | CNN architecture translated from a diagram into PyTorch |

## Building locally

```bash
pip install -r requirements.txt
jupyter-book build .
```

Open `_build/html/index.html` in your browser to preview.

## Publishing updates

```bash
jupyter-book build .
git add .
git commit -m "Update portfolio"
git push
ghp-import -n -p -f _build/html
```
