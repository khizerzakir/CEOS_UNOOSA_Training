---
title: EO Tutorial with cubo, xarray, and Dask
---

# EO Tutorial with `cubo`, xarray, and Dask

A compact teaching package for a 90-minute session on **medium-resolution Earth Observation**, focused on **climate resilience** and **risk monitoring**.

![Earth view](assets/earth_modis_globe.jpg)

## What is included

- a **slide deck** introducing Dask, API calling, xarray, and the tutorial flow
- a **Jupyter notebook** using **`cubo`** as the single user-facing API
- two simple regional examples:
  - **Africa:** MODIS NDVI/EVI
  - **Asia:** Sentinel-3 OLCI coastal quicklook

## Open the tutorial

- [Rendered tutorial notebook](assets/cubo_xarray_dask_tutorial.html)
- [Download the notebook (`.ipynb`)](assets/cubo_xarray_dask_tutorial.ipynb)

## Slides

- [Download the presentation (`.pptx`)](assets/cubo_xarray_dask_presentation.pptx)

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
