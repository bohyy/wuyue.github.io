# Yue Wu Portfolio

Published at https://bohyy.github.io/wuyue.github.io/

This repository contains the static production build of the portfolio. GitHub Pages serves the `main` branch at its root; `.nojekyll` keeps the Vite output unprocessed.

To update, run `npm run build` in the source project, copy `dist/` into this repository excluding development-only `qa/` files, and commit and push the resulting files. The previous site remains available in git history. Legacy HTML page URLs redirect to the new homepage.
