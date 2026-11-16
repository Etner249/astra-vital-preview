# ASTRA VITAL — PREVIEW build (integration test only)

This repository only hosts a **preview** of the branch `academic-integration` of
[Etner249/astra-vital](https://github.com/Etner249/astra-vital) so that the GitHub Pages ↔ Render
integration can be tested from the same origin (`https://etner249.github.io`) **without touching the
official URL** https://etner249.github.io/astra-vital/ (the version submitted to NASA Space Apps 2026).

- Frontend: built from `academic-integration` (`AV_API_BASE=https://astra-vital-api-preview.onrender.com/api/v1 python build.py`)
- Backend: Render service `astra-vital-api-preview` (branch `api-integration` of
  [astra-vital-flask-sqlite](https://github.com/Etner249/astra-vital-flask-sqlite), Blueprint `render.preview.yaml`)
- `nasa-2026/index.html`: byte-identical copy of the version submitted to NASA (commit `8df773b`).

Can be deleted after the integration is approved. Team NYXARA NOVA · educational prototype · not a medical device.
