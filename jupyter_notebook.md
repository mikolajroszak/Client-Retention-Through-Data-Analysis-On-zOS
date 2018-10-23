# Client Retention Demo    

Analyze client credit card data with using Python and Jupyter Notebooks via IBM Open Data Analytics for z/OS.

# Short Description

For this demo we are pretending we are a bank with Client Retention Issues.  Our customers are churning (leaving the bank).  Using Jupyter Notebooks with IBM Open Data Analytics for z/OS (IzODA) to look at credit card transactional data. With the various Python libraries and the optimized data layer provided by IzODA, we can create robust data visualizations that allow us to look for key features as to why a customer may want to leave our bank.

# Offering Type

Analytics

# Introduction

This demo is an exploratory Jupyter Notebook.  It analyzes customer data, and customer credit card transactions data which is on the Mainframe, to discover potential factors of why they would leave the bank.

When giving the demo, you need to setup the backstory.  The backstory of the demo is that you are a bank that is experiencing customer retention issues, or in data scientist terms, Customer Churn.  Now, the data science team, you, will need to analyze the data to see what features are good indicators of a potential churn.

This demo is written in Python and includes many of the top Python libraries like Pandas and Matplotlib.  It is also doing machine learning with Scikit-Learn.

# Author
by David Rice

# Code
* [Client Retention Demo on Github](https://github.com/IzODA/examples/blob/master/python/client_retention_demo.ipynb)

# Video
* [Client Retention Demo on Youtube](https://youtu.be/M_5UA7rgYgw)

# Overview
The Client Retention Demo uses two sets of data, a client information table with 6001 records, and a credit card transaction table with ~1.5million records.  In this journey will demonstrate how to use z/OS data with modern programming languages to analyze these two sets of data for key prediction features.

When the reader has completed this journey, they will understand how to:
* Use [Jupyter Notebooks](http://jupyter.org/) to load, visualize, and analyze data
* Run Notebooks in [IBM Open Data Analytics](???)
* create a predictive model using [scikit-learn](http://scikit-learn.org/stable/)

# Flow

![](architecture.png)

1. The developer opens Jupyter Notebook server on z/OS
2. then starts the Client Retention Demo notebook
2. the two sets of data are loaded into the Notebook.
3. The Notebook analyzes the credit card and customer data.
4. The Developer can interactively change charts and graphs.

# Included Components
* [IBM Open Data Analytics for z/OS](???)

# Featured Technologies
* [Jupyter Notebooks](http://jupyter.org/): An open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text.

* [scikit-learn](http://scikit-learn.org/stable/) Python Machine Learning library

* [Matplotlib](https://matplotlib.org/)/[Seaborn](https://seaborn.pydata.org/): Python libraries used to visualize data.
