# The Client Retention Demo

This demo is an exploritory Jupyter Notebook.  It analyzes customer data, and customer credit card transactions data which is on the Mainframe, to discover potential factors of why they would leave the bank.

When giving the demo, you need to setup the backstory.  The backstory of the demo is that you are a bank that is experiencing customer retention issues, or in data scientist terms, Customer Churn.  Now, the data science team, you, will need to analyze the data to see what features are good indicators of a potential churn.

This demo is written in Python and includes many of the top Python libraries like Pandas and Matplotlib.  It is also doing machine learning with Scikit-Learn.


ADD ARCHETECTURE DIAGRAM HERE

## Flow

1. A Data Scientest interacts with a Web UI.
1. The Web UI is the browser based iuser interface for Jupyter Notebook.
1. Jupyter Botebook is part of IzODA, running on z/OS.
1. A VSAM Dataset is being accessed via a virtural table defined in ODL.
1. DSDBC queries ODL for the VSAM Date.

## Included components

* [IzODA](https://izoda.github.io): An assembly of key open source and proprietary technologies that allow data scientists and application developers to analyze and visualize the large volumes of data hosted on IBM Z.
* [Conda](https://conda.io/docs/index.html): Conda is an open source package management system and environment management system.
* [Jupyter Notebook](http://jupyter.org/): An open source web application that allows you to create and share documents that contain live code, equations, visualizations, and explanatory text.
* [Pandas](https://pandas.pydata.org): An open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.
* [Scikit-learn](http://scikit-learn.org/stable/): A simple and efficient tools for data mining and data analysis
* [MatPlotLib](https://matplotlib.org): A Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.
* [Seaborn](https://seaborn.pydata.org): A Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
* [Numpy](http://www.numpy.org): Is the fundamental package for scientific computing with Python. It contains among other things
* [DSDBC](https://anaconda.org/izoda/dsdbc)
* [ODL]

## Featured technologies

* [Artificial Intelligence](https://medium.com/ibm-watson): Artificial intelligence can be applied to disparate solution spaces to deliver disruptive technologies.
* [Data Science](https://medium.com/ibm-watson): Systems and scientific methods to analyze structured and unstructured data in order to extract knowledge and insights.
* [Python](https://www.python.org/): Python is a programming language that lets you work more quickly and integrate your systems more effectively.

# Steps

Either run locally:

1. [Clone the repo](#1-clone-the-repo)
2. [Run Jupyter Notebooks](#2-run-jupyter-notebooks)

## Run locally

### 1. Clone the repo

Clone the update_with_new_name locally. In a terminal, run:

```
$ git clone this_needs_to_be_updated
```

### 2. Run Jupyter Notebooks

The code included in this Code Pattern runs in a Jupyter Notebook.

* Start your Jupyter Notebooks. Starting in your `ensure-load-fairness-aif360` cloned repo directory will help you find the notebook and the output as described below. Jupyter Notebooks will open in your browser.

   ```
   cd update_this
   jupyter notebook
   ```

* Navigate to the `notebooks` directory and open the notebook file named `credit_scoring.ipynb` by clicking on it.


# Links

* [IzODA](https://izoda.github.io)
* [Live Client Retention Demo](https://www.youtube.com/watch?v=M_5UA7rgYgw&t=135s)


# Learn more

* **WE NEED TO ADD A SECTION ON IZODA/MAINFRAME**:
* **Artificial Intelligence Code Patterns**: Enjoyed this Code Pattern? Check out our other [AI Code Patterns](https://developer.ibm.com/code/technologies/artificial-intelligence/).
* **Data Analytics Code Patterns**: Enjoyed this Code Pattern? Check out our other [Data Analytics Code Patterns](https://developer.ibm.com/code/technologies/data-science/)
* **AI and Data Code Pattern Playlist**: Bookmark our [playlist](https://www.youtube.com/playlist?list=PLzUbsvIyrNfknNewObx5N7uGZ5FKH0Fde) with all of our Code Pattern videos


# License
[Apache 2.0](LICENSE)
