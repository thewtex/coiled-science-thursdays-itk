# Jupyter, Microscopy, and On-demand Dask Cloud Clusters

https://www.eventbrite.com/e/jupyter-microscopy-and-on-demand-dask-cloud-clusters-tickets-153332205755

## Introduction

Matt McCormick, who works at Kitware maintaining the Insight Toolkit (ITK) library, joins Hugo Bowne-Anderson to discuss large-scale microscopic image visualization and analysis with on-demand Dask cloud clusters.

Web-based methods are well-suited to solve scientific microscopy challenges such as large images, remote datasets, and reproducibility.

We’ll discuss how to apply the PyData stack (dask, jupyter, itk, scikit-image, xarray, zarr, and itkwidgets) inside interactive Jupyter notebooks to gain insights from 2D and 3D microscopy datasets. We will discuss web-based image visualization, image data storage for the web, and distributed image processing in the cloud.

After attending, you’ll know:

- How to create a consistent software environment to use Jupyter with Coiled Dask clusters
- How to interactively explore your 3D microscopy volumes in Jupyter with itkwidgets
- How to store your images for distributed processing with Dask and the PyData stack

Join us Thursday, May 27th at 5 pm US Eastern time by signing up here and dive into the wonderful world of large-scale microscopic image visualization and analysis with Dask!

## Installation

[Install mambaforge](https://github.com/conda-forge/miniforge), then:

```
mamba env create --file environment.yml --name coiled-itk
mamba activate coiled-itk
python -m jupyter notebook
```
