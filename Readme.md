# Building a NLP ETL Pipeline and Conducting Analysis on Eminem Lyrics

Building a pipeline in python to clean and pre-process song lyrics to perform analysis. Eminem's lyrics were scrapped from [lyricsGenius](https://github.com/johnwmillr/LyricsGenius), a Python library by [Johnwmillr](https://github.com/johnwmillr) on December 22, 2020.

###### Analysis performed:
- WordCloud (***EminemWC.png***)
- Text Analysis
- Sentiment Analysis

### Frameworks
- lyricsgenius - Library for scrapping data from [Genius.com](https://genius.com)
- Pandas - Library for Dataframe manipulation
- Json - Json processing library 
- Numpy - Library used for large, high-level mathematics
- langdetect - Language detection library
- NLTK - Natural Language processing ToolKit
- PIL - Image processing library
- Wordcloud - Library used for making wordclouds
- Matplotlib - Library used for visualizations

### How to run 

You can clone the whole repo and run the **.ipynb** files on Jupyter Notebook or Google Collab. Comments and detailed explaination of the code are in these files as well.

### Files 
- [***Extract.ipynb :***](/Extract.ipynb)  Code used to scrape Eminem's lyrics
- [***TransformLoad.ipynb :***](/TransformLoad.ipynb) Code for data cleaning and pre-processing
- ***Test.db:***  DataBase to store data from TransformLoad.ipynb
- [***NLTKAnalysis.ipynb :***](/NLTKAnalysis.ipynb) Code for WordCloud and NLP analysis

**NOTE :** The resulting files when running the above files will be saved in the working directory. However, all the output files are stored in files folder here for organizing reasons. 

![Eminem WordCloud](https://github.com/thebadcoder96/Eminem/blob/master/files/EminemWC.png?raw=true)

