# commercial_storage_analysis

As subject matter experts in the energy industry, we understand the various technologies and their characteristics at the wholesale level very well (think large power plants and battery systems, often referred to as "front-of-the-meter"). However, we lacked in-depth understanding of the key attributes & drivers for smaller scale batteries in commercial buliding settings (< 1 MW).

The goal of this study is to optimize the dispatch of a commercial-scale battery storage system to better understand its behavior in various environments and its key operational constraints.

This repository contains all of our modelling (ETL pipelines, machine learning models, dispatch algorithm) and analyses (data exploration, key insights).

## Table of Contents
1. [Installation](#installation)
2. [File Descriptions](#file-descriptions)
3. [Results](#results)
4. [Licensing](#licensing)

## Installation
To run the scripts in the Jupyter notebooks, you will only require the Anaconda distribution of Python (v3.0+).

## File Descriptions
**Notebooks**

There are 5 notebooks that comprise this analysis:
1. [Commercial Load Forecast.ipynb](https://github.com/jbbae/commercial_storage_analysis/blob/master/Commercial%20Load%20Forecast.ipynb): Full machine learning pipeline (i.e. ETL, training, predicting) for forecasting of the reference building load.
2. [Storage Dispatch Algorithm.ipynb](https://github.com/jbbae/commercial_storage_analysis/blob/master/Storage%20Dispatch%20Algorithm.ipynb): Dispatch algorithm for the energy storage unit.

**Output**

In addition to the above notebooks, there also are a few key data files:
1. [Seattle_Load_H.csv](https://github.com/jbbae/commercial_storage_analysis/blob/master/Seattle_Load_H.csv): 5-year hourly load forecast (2012-2016)

## Results
We will publish our results & findings in a series of 2 blog posts:
__1. [Storage + Commercial Buildings (Part 1): Load Forecasting]()__
__2. Storage + Commercial Buildings (Part 1): Energy Storage Dispatch:__ Coming Soon

## Licensing

This analysis is powered by public data provided by [OpenEI](https://openei.org/wiki/OpenEI:About) and [Kaggle](https://www.kaggle.com/selfishgene/historical-hourly-weather-data/downloads/historical-hourly-weather-data.zip/21).