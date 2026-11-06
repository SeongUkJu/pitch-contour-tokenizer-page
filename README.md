# pitch-contour-tokenizer — Project Page

Demo page for "Pitch Contour Tokenization using VQ-VAE and Its Application on
Korean Traditional Music Analysis" (ISMIR 2026).

Paper: https://arxiv.org/abs/2608.10979 · Code: https://github.com/MALerLab/pitch-contour-tokenizer

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deployment

Push to `main`; the GitHub Actions workflow (`.github/workflows/static.yml`)
deploys the repository root to GitHub Pages automatically
(Settings → Pages → Source: GitHub Actions).

## Asset status

All media under `static/images/` and `static/audio/` are final: decoded-token
contour plots and concatenated audio excerpts generated from the paper
checkpoints (`sigimsae/`, `mode_token/`), manually transcribed staff notation,
and the architecture overview figure.

Built from [paper-page-template](https://github.com/liu-qilong/paper-page-template)
(Academic Project Page Template lineage, CC BY-SA 4.0).
