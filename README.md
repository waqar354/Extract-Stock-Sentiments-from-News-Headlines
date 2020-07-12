# Extract Stock Sentiment from News Headlines

This is a project offered by Datacamp to analyze the sentiments and emotions from Headlines from Finviz.

## Getting Started

Getting started with this project, you will require to have a hands-on grip over basics of Intermediate Python for Data Science, Data Manipulation with Pandas, and Basics of Natural Language Processing. 


To work with this project, I'll suggest you to use Jupyter Notebook to work with this .ipynb file. And make sure to set the correct path for datasets in the code. It would be better if you'll create a dataset directory in the same folder where you have placed the .ipynb file.

## Prerequisites
The following are the prerequisites for this project.

### Datasets

The datasets used in this project are raw HTML files for Facebook (FB) and Tesla (TSLA) stocks from FINVIZ.com, a popular website dedicated to stock information and news.

**Note**: *Datasets (HTML Files) are given along with .ipynb file.*


### Installation and Import
You need to import the Beautiful Soup library from bs4.

```python
from bs4 import BeautifulSoup
```
After this, you must have to import os library.
```python
import os
```
You will also need matplotlib.pyplot and pandas libraries which can be imported by,
```python
import matplotlib.pyplot as plt
import pandas as pd
```
**And the most important library which you have to install and import for this project is NLTK. Make Sure you have an active internet connection to download and install it.**
```python
import nltk
nltk.download('vader_lexicon')

from nltk.sentiment.vader import SentimentIntensityAnalyzer
```

After this you are good to go with the project.

## Contributor

* **WAqar Rao** - *Completed this project from Datacamp* - [WAqar Rao](https://github.com/waqar354)

