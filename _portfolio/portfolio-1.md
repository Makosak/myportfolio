---
title: "Intro to Spatial Analysis"
excerpt: "A series of computational notebooks to introduce spatial data concepts with Python. <br/> <img src='https://raw.githubusercontent.com/Makosak/myportfolio/refs/heads/master/images/urbana.png'>"
collection: portfolio
---

For **GGIS 371: Spatial Analysis** taught in Spring 2026 at UIUC, I developed a series of computational notebooks to align students coming from different experiences (code, no code, some GIS coursework, no GIS coursework). 

We used the new classic, [Geographic Data Science](https://geographicdata.science/book/) by Rey et al (2025) to guide coding and learning throughout the course. The first three labs worked with data and concepts from the first three chapters of the text, reframed slightly to be more beginner-friendly. We used the UIUC [CyberGISX](https://cybergisxhub.cigi.illinois.edu/) environment as a standardized cloud interface for working with Python.

## [Week 1: Intro to Python](https://github.com/Makosak/myportfolio/blob/master/files/Ch1-Intro2Py.ipynb)
In the first week's lab, our goal was to get familiar with *applied programming*, using Python in the CyberGISX environment. That means creating our first Jupter Notebook! Specific objectives include:

- Setting up a coding environment in CyberGISX
- Learning basic file management
- Subset & filter non-spatial data

By the end, we'll be comfortable with the basics of working with data in a coding notebook. We'll also consider what is *missing* when we aren't leveraging the spatial dimension of the data, and start to brainstorm troubleshooting approaches.

## Week 2: Geocomputational Workbooks

This week, coding goals are to:

- Get more familiar with Jupyter Notebooks
- Open & explore geospatial data using `geopandas`
- Turn a CSV with coordinates into geospatial data

## Week 3: Spatial Data

This week, we're diving into the details of Spatial Data. In our Python computational environment, we will learn how to work with three main types of spatial data structures: geographic tables, surfaces, and networks. Coding goals are to:

- Review the basics of geographic tables
- Explore surface data structures using `xarray` and `rioxarray`
- Explore spatial graph structures using data from `osmx`