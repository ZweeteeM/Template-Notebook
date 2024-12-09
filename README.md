# Aircraft Wildlife Strike Analysis: Enhancing Aviation Safety

# Flight Analytics<div id="main image" align="center">
<div id="main image" align="center">
  <img src="https://github.com/ZweeteeM/Template-Notebook/blob/main/68a9ec2c467ac1323c66245f09b54b0e.jpg" width="700" height="500" alt=""/>
</div>

## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. Surprise Library Models](#library)
* [6. Streamlit](#streamlit)

## 1. Project Overview <a class="anchor" id="project-description"></a>

Wildlife strikes are a critical safety concern in aviation, with incidents potentially leading to costly repairs, flight delays, and safety hazards. This project aims to analyze historical wildlife strike data to identify patterns, high-risk species, and factors contributing to damage severity. The insights generated will aid in developing mitigation strategies to enhance aviation safety and minimize wildlife impacts.

## 2. Dataset <a class="anchor" id="dataset"></a>

The dataset used in this analysis includes detailed records of wildlife strikes on aircraft. Key features include:

Incident Details: Year, month, day, and operator information. 
Wildlife Information: Species involved, size, and number of strikes. 
Impact Data: Severity of damage (minor or major) and affected aircraft components. 
The dataset consists of 66 columns with no missing values, covering thousands of incidents reported across multiple years. 


## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:

- Programming Languages: Python
- Machine Learning Libraries: Scikit-learn
- Data Processing: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Deployment: Streamlit

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for ones projects, there are many ways to do this. Make sure to regularly update this section. This way, anyone who clones the repository will know exactly what steps to follow to prepare the necessary environment. 

## 5. Surprise Library Models <a class="anchor" id="mlflow"></a>

The Surprise library is a powerful Python scikit for building and analyzing recommender systems. It includes various algorithms for collaborative filtering, such as Singular Value Decomposition (SVD), Slope One, and Non-Negative Matrix Factorization (NMF). Surprise simplifies the process of working with recommendation data, providing built-in datasets and utilities for data loading, splitting, and evaluation. It also supports grid search for hyperparameter tuning and cross-validation, making it easier to develop and assess the performance of recommendation models. With its comprehensive suite of tools, Surprise is an excellent choice for developing accurate and efficient recommender systems.

## 6. Streamlit<a class="anchor" id="streamlit"></a>

### What is Streamlit?

[Streamlit](https://www.streamlit.io/)  is a framework that acts as a web server with dynamic visuals, multiple responsive pages, and robust deployment of your models.

In its own words:
> Streamlit ... is the easiest way for data scientists and machine learning engineers to create beautiful, performant apps in only a few hours!  All in pure Python. All for free.

> It’s a simple and powerful app model that lets you build rich UIs incredibly quickly.
>
> 
[Streamlit](https://www.streamlit.io/)  takes away much of the background work needed in order to get a platform which can deploy your models to clients and end users. Meaning that you get to focus on the important stuff related to data, and can largely ignore the rest. This will allow you to become a lot more productive.  

##### Description of files

For this repository, we are only concerned with a single file:

| File Name              | Description                       |
| :--------------------- | :--------------------             |
| `base_app.py`          | Streamlit application definition. |


