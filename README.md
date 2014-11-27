EnerNOC-100-Building-Open-Dataset-Analysis
==========================================

#EnerNoc - Open data to faciliate research and development

###by: [Clayton Miller](https://www.researchgate.net/profile/Clayton_Miller2) - Nov, 27 2014
###Part of a series of Commercial Open Building Datasets on [datadrivenbuilding.org](http://datadrivenbuilding.org/)

This notebook will open and explore the [EnerNOC](http://open.enernoc.com/data/) dataset of 100 anonymized buildings for the 2012 year. The goal of this notebook is to explore and visualize some of the data with the annotation capable in a notebook.

This dataset is downloadable from the site above and is licensed under a [Creative Commons Attribution-NonCommercial 3.0 Unported License](http://creativecommons.org/licenses/by-nc/3.0/). 

I have always been very interested in the massive amounts of raw data that [EnerNoc](http://www.enernoc.com/) is accumulating -- it would be a dream to play around with that amount and magnitude of data. I was super pleasantly surprised to stumble across  EnerNOC's [*Open Source for an Open Grid*](http://open.enernoc.com/data/) site after reading about it from [Nipun Batra's paper](http://combed.github.io/#portfolio) about commercial building dissaggregation. 

##First, we load the appropriate libaries:
- [Pandas](http://pandas.pydata.org/)
- [OS](https://docs.python.org/2/library/os.html)
- [matplotlib](http://matplotlib.org/)

It's not explicity stated that the data is `kW` instantaneous but we will make that assumption.

