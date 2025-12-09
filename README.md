# UKHSA Measles and MMR Vaccine Dashboard

## Overview

This repository contains the code for an interactive data dashboard built using **Python**, **Pandas**, **Matplotlib**, and **Jupyter Widgets (ipywidgets)**. The dashboard is designed to be rendered using **Voila** and visualises two key metrics from the UK Health Security Agency (UKHSA) data:

1.  **Weekly Measles Cases** across UKHSA regions.
2.  **Childhood MMR Vaccination Coverage (MMR1 & MMR2)** in England.

The primary goal is to illustrate the crucial link between population immunity (MMR coverage) and infectious disease activity (measles cases), allowing users to explore trends and regional differences.

## Features

* **Interactive Controls:** Select multiple regions and switch between linear/log scales for the Measles Cases graph.
* **Time Series & Bar Charts:** View measles case trends over time and compare MMR coverage percentages across different age milestones and reporting years.
* **Live Data Refresh:** A button is included to fetch the most up-to-date data directly from the UKHSA Dashboard API.
* **Data Caching:** Automatic caching to JSON files ensures the dashboard can still load with the last successful data snapshot even if the API is temporarily unavailable.

## Prerequisites

To run this dashboard locally, you will need the following installed:

* Python (3.7+)
* Jupyter Notebook or JupyterLab
* Voila (to render the interactive notebook as a standalone dashboard)

### Key Python Libraries

You can install the required libraries using `pip`:

```bash
pip install pandas numpy matplotlib requests ipywidgets voila

https://mybinder.org/v2/gh/daniel-d-dev/ukhsa-measles-mmr-dashboard/HEAD?urlpath=voila%2Frender%2FDashboard.ipynb%3F
