# Sticky_Reviews1
The Data Incubator Capstone Project

Sticky reviews are consumer reviews that start a sequence of low-scorring reviews.
It is important for every seller to identify sticky reviews.
In this project I first define and later build a classifier for spotting sticky reviews.


I start out with the Amazon Reviews data (1.5Gb) downloaded from:
http://jmcauley.ucsd.edu/data/amazon/

##### 01 Sticky Reviews histogram contains the initial analysis (histograms) that defines the sticky reviews
but not the initial steps of downloading the data and the preprocessing, which I did in a different notebook (to be uploaded soon)

##### 03_Sticky_Reviews_LDA_sticky_10topics I train and visualize a LDA model for the sticky reviews
using gensim and pyLDAvis

##### 04_WordCloud_gensim_tfidf_function
A nice visualization of text used in sticky reviews
I plot the word-cloud of the sticky reviews and the non-sticky reviews (dip reviews
