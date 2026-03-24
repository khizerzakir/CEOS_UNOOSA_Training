---
title: Tutorial overview
---

<link rel="stylesheet" href="assets/site.css">

# Tutorial overview

This tutorial keeps the user-facing workflow simple:

> **`cubo` for data access, `xarray` for analysis, Dask for scaling**

<div class="actions">
  <div class="action-card">
    <strong>Rendered HTML</strong>
    <a href="assets/cubo_xarray_dask_tutorial.html">Open notebook as HTML</a>
  </div>
  <div class="action-card">
    <strong>Run in Google Colab</strong>
    <a href="https://colab.research.google.com/github/khizerzakir/github_pages_cubo_tutorial/blob/main/cubo_xarray_dask_tutorial.ipynb" target="_blank" rel="noopener">Launch cubo tutorial in Colab</a>
  </div>
  <div class="action-card">
    <strong>EO climate notebook</strong>
    <a href="https://colab.research.google.com/github/khizerzakir/github_pages_cubo_tutorial/blob/main/eo_climate_resilience_tutorial_africa_asia.ipynb" target="_blank" rel="noopener">Launch EO climate notebook in Colab</a>
  </div>
</div>

## Concepts covered

- what a remote EO cube call looks like
- how `xarray` labels dimensions like `time`, `band`, `y`, `x`
- why Dask-backed chunks matter
- why `.compute()` should happen late
- how the same `cubo.create(...)` call can target:
  - **Google Earth Engine**
  - **default STAC access**
  - **another STAC endpoint**

## Notebook

- [Rendered HTML notebook](assets/cubo_xarray_dask_tutorial.html)
- [Raw notebook](assets/cubo_xarray_dask_tutorial.ipynb)
- [Open cubo tutorial in Colab](https://colab.research.google.com/github/khizerzakir/github_pages_cubo_tutorial/blob/main/cubo_xarray_dask_tutorial.ipynb)
- [Open EO climate tutorial in Colab](https://colab.research.google.com/github/khizerzakir/github_pages_cubo_tutorial/blob/main/eo_climate_resilience_tutorial_africa_asia.ipynb)

<div class="inline-note">
  Colab runtime tip: use <strong>Runtime → Run all</strong> after package installation cells complete.
</div>

## Regional examples

### Africa
<div class="figure-frame">
![Africa example](assets/africa_modis_landcover.jpg)
</div>

### Asia
<div class="figure-frame">
![Asia example](assets/asia_floods.jpg)
</div>
