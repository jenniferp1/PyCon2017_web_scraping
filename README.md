# An introduction to APIs, RSS, and Scraping
## Fantastic Data and Where To Find Them
## PyCon, Portland, 2017

This repository contains the notebooks, slides, and sample code for the tutorial given at [PyCon](https://us.pycon.org/2017/) on Wendesday, May 17, 2017.

Whether you’re building a custom web application, getting started in machine learning, or just want to try something new, everyone needs data. And while the web offers a seemingly boundless source for custom data sets, the collection of that data can present a whole host of obstacles. From ever-changing APIs to rate-limiting woes, from nightmarishly nested XML to convoluted DOM trees, working with APIs and web scraping are challenging but critically useful skills for application developers and data scientists alike. In this tutorial, we’ll introduce RESTful APIs, RSS feeds, and web scraping in order to see how different ingestion techniques impact application development. We’ll explore how and when to use Python libraries such as `feedparser`, `requests`, `beautifulsoup`, and `urllib`. And finally we will present common data collection problems and how to overcome them.

We’ll take a hands-on, directed exercise approach combined with short presentations to engage a range of different APIs (with and without authentication), explore examples of how and why you might web scrape, and learn the ethical and legal considerations for both. To prepare attendees to create their own data ingestion scripts, the tutorial will walk through a set of examples for robust and responsible data collection and ingestion. This tutorial will conclude with a case study of Baleen, an automated RSS ingestion service designed to construct a production-grade text corpus for NLP research and machine learning applications. Exercises will be presented both as Jupyter Notebooks and Python scripts.

## Contents

There is a directory for each topic that contains the tutorial notebook and sample code. The slides were [created](http://echorand.me/presentation-slides-with-jupyter-notebook.html) with Jupyter notebook and [reveal.js](https://github.com/hakimel/reveal.js/). They are hosted on [GitHub Pages](https://pages.github.com/) and can be viewed [here](https://nd1.github.io/pycon_2017/).

## Getting Started

Step one is to clone or [download](https://github.com/nd1/pycon_2017/archive/master.zip) the repository, unzip it and then cd into the project directory.

Note, this code requires [Python 3](https://www.python.org/downloads/) or [Anaconda](https://www.continuum.io/downloads) to run, as well as several third party libraries. Make sure that you have [Jupyter notebook](http://jupyter.readthedocs.io/en/latest/install.html) installed, and if you're using Python that you have [pip](https://pip.pypa.io/en/stable/installing/) installed.  One you do, you can install the required third party dependencies as follows:

```
$ pip install -r requirements.txt
```

or

```
$ conda install --yes --file requirements.txt
```
