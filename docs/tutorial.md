---
title: Tutorial overview
---

<link rel="stylesheet" href="assets/site.css">

<div class="top-nav">
  <a href="./index">Home</a>
  <a href="./tutorial">Tutorial</a>
  <a href="./slides">Slides</a>
</div>

# Tutorial overview

This tutorial keeps the user-facing workflow simple:

> **`cubo` for data access, `xarray` for analysis, Dask for scaling**

## Table of Contents

* TOC
{:toc}

<div class="actions">
  <div class="action-card">
    <strong>Rendered HTML</strong>
    <a href="assets/cubo_xarray_dask_tutorial.html">Open notebook as HTML</a>
  </div>
  <div class="action-card">
    <strong>Rendered HTML</strong>
    <a href="assets/eo_climate_resilience_tutorial_africa_asia.html">Open EO climate notebook file</a>
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

## Other tutorial in this project

The second tutorial focuses on climate resilience applications across Africa and Asia:

- [EO climate resilience notebook](assets/eo_climate_resilience_tutorial_africa_asia.ipynb)
- includes AOI setup for `gode_afric` and `ban_asia`
- uses MPC/STAC and cubo-friendly workflows for participants without GEE
- includes NDVI snapshots, search patterns, and integrated climate-context examples

## Using medium-resolution EO data: key points

- medium-resolution products are strong for regional monitoring and trend analysis
- revisit frequency is often more important than fine spatial detail for resilience signals
- keep spatial and temporal windows small first, then scale with Dask
- always check scaling factors, QA flags, and product-specific metadata
- combine EO indicators with rainfall and local context before interpretation


## Study Areas

<div class="image-grid">
  <img src="assets/gode_africa.png" alt="gode_africa">
  <img src="assets/ban_asia.png" alt="ban_asia">

</div>

- [Go back to the home page](./index)