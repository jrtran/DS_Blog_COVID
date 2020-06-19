# DS_Blog_COVID

## Table of Contents

1. [Project Motivation](#motivation)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Motivation <a name="motivation"></a>

This repository is for Udacity's Data Science Nanodegree blog post project, and the subject is COVID-19 cases in California. I chose this subject because of its ubiquitous and far-reaching impact on our daily lives, and because effective analysis can guide policymakers toward life-saving and life-preserving strategies. Just as in any science, even "failed results" or "finding nothing" can be useful, because they help us to improve our methods while avoiding previous pitfalls. In this project, I sought to answer the following questions:
* How are overall cases and deaths related?
* Do deaths have any relationship between the number of ICU cases?
* What is the relationship between the number of suspected cases and the number of actual cases?

## Installation <a name="installation"></a>

Older versions of certain packages may work, but have not been tested. The libraries used were as follows:
* Anaconda distribution of Python (>=3.5)
* pandas (>= 1.0.0)
* NumPy (>= 1.0)
* JupyterLab (>= 1.0)
* plotly (>= 4.7.0)
   - The JupyterLab extension should also be installed, as detailed [here](https://plotly.com/python/getting-started/#jupyterlab-support-python-35).

## File Descriptions <a name="files"></a>

The files in this repository include:
* A JupyterLab notebook that describes the entire process of gathering, cleaning, analyzing, and visualizing the data.
* The original dataset (in .csv format) and an accompanying codebook (in .xlsx format), both pulled from the California Human Health and Services Agency [data repository](https://healthdata.gov/dataset/california-covid-19-hospital-data-and-case-statistics).
* A geocodes file in .xlsx format, used for creating the interactive county maps via FIPS codes.

## Results <a name="results"></a>

The corresponding Medium blog post, which summarizes and describes the main findings of this project, can be found [here](https://medium.com/@jrtran/covid-19-in-california-a-county-by-county-overview-eee334f8a159). A brief summary is as follows:
* How are overall cases and deaths related? The mortality rate remains below 5% for the vast majority of counties, including the most affected (e.g., Los Angeles County). 
* Do deaths have any relationship between the number of ICU cases? No clear relationship was found, even though ICU cases make up a sizable portion of all COVID-19 hospital patients. In fact, we cannot even conclude that ICU patients are more likely to sucuumb to the disease than non-ICU patients.
* What is the relationship between the number of suspected cases (including symptomatic patients awaiting test results) and the number of actual cases? Again, no clear relationship was found. Moreover, due to the variance in suspected patients, it's unlikely that we can use it to effectively predict the number of actual cases on a county-by-county basis.

## Licensing, Authors, and Acknowledgements <a name="licensing"></a>

The licensing for the data is included in the JupyterLab notebook. Udacity's Data Science Nanodegree course provided the template for this README.
