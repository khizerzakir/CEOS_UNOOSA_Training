---
title: Tutorial overview
---

# Tutorial overview

This tutorial keeps the user-facing workflow simple:

> **`cubo` for data access, `xarray` for analysis, Dask for scaling**

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

## Regional examples

### Africa
![Africa example](assets/africa_modis_landcover.jpg)

### Asia
![Asia example](assets/asia_floods.jpg)
