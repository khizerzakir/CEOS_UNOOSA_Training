---
title: EO Tutorial with cubo, xarray, and Dask
---

<link rel="stylesheet" href="assets/site.css">

# EO Tutorial with `cubo`, xarray, and Dask

A compact teaching package for a 90-minute session on **medium-resolution Earth Observation**, focused on **climate resilience** and **risk monitoring**.

![Earth view](assets/earth_modis_globe.jpg)

<div class="hero">
  <p><strong>Quick start:</strong> open the tutorial notebook in your browser, download the notebook if needed, or launch directly in Google Colab.</p>
</div>

<div class="actions">
  <div class="action-card">
    <strong>Rendered notebook</strong>
    <a href="assets/cubo_xarray_dask_tutorial.html">Open tutorial in browser</a>
  </div>
  <div class="action-card">
    <strong>Notebook file</strong>
    <a href="assets/cubo_xarray_dask_tutorial.ipynb">Download .ipynb</a>
  </div>
  <div class="action-card">
    <strong>Run in Google Colab</strong>
    <a href="https://colab.research.google.com/github/khizerzakir/github_pages_cubo_tutorial/blob/main/cubo_xarray_dask_tutorial.ipynb" target="_blank" rel="noopener">Open cubo tutorial in Colab</a>
  </div>
  <div class="action-card">
    <strong>EO climate notebook in Colab</strong>
    <a href="https://colab.research.google.com/github/khizerzakir/github_pages_cubo_tutorial/blob/main/eo_climate_resilience_tutorial_africa_asia.ipynb" target="_blank" rel="noopener">Open EO climate tutorial in Colab</a>
  </div>
</div>

## What is included

- a **slide deck** introducing Dask, API calling, xarray, and the tutorial flow
- a **Jupyter notebook** using **`cubo`** as the single user-facing API
- two simple regional examples:
  - **Africa:** MODIS NDVI/EVI
  - **Asia:** Sentinel-3 OLCI coastal quicklook

## Slides

- [Download the presentation (`.pptx`)](assets/cubo_xarray_dask_presentation.pptx)
- [Open slides page](slides.html)

## Run in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/khizerzakir/github_pages_cubo_tutorial/blob/main/cubo_xarray_dask_tutorial.ipynb)

[![Open EO Climate Notebook In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/khizerzakir/github_pages_cubo_tutorial/blob/main/eo_climate_resilience_tutorial_africa_asia.ipynb)

<div class="inline-note">
  If Colab opens with a file-not-found error, ensure your default branch is <strong>main</strong> and both notebooks are committed to GitHub.
</div>

## Suggested repo structure

```text
docs/
  index.md
  assets/
    cubo_xarray_dask_tutorial.ipynb
    cubo_xarray_dask_tutorial.html
    cubo_xarray_dask_presentation.pptx
```

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. In **Settings → Pages**, choose **Deploy from a branch**.
3. Select your main branch and the **`/docs`** folder.
4. Save, then open the published site URL.
