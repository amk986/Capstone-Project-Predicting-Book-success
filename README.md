# Predicting a book's literary success using specific books features

## Table of Contents
1. [Introduction and Overview](#introduction)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [References](#references)


### Introduction and Overview
The purpose of this project is to analyze and predict book's overall rating success using various machine learning models. For the analysis, I have utilized datasets collected in 2017 provided by Goodreads which contains specific feature information such as the authors, publishers/publication companies, books average ratings, reviews, publication years, length of books (by pages), languages, genre, fiction/nonfiction classification, authors average ratings, books and authors ratings counts. The Goodreads dataset is structured data that contains information on  2.36M books with approximately 39 feature variables.

After collecting the data, and proceeding to explore and clean the dataset as much as possible, I wanted to analyze further the possible research questions:
1. Would a nonfiction or fiction book prove to be more successful? Sucess being measured by the book's overall rating.
2. Does author's historical ratings contribute to the success of the next book he/she would publish?
3. Does the length of a book affect a book's literary success?
4. Are books part of a series more successful than a book not part of a series?

### Technologies
Python3 required
import packages specified in notebooks

### Installation
There are seperate notebooks for the EDA portion of the analysis and the various Machine Learning models I utilized to achieve the best accuracy result. 
1. EDA_final.ipynb: 
    - Loading in json files: goodreads books, goodreads authors, goodreads genre, and goodreads series
    - Cleaning and creating feature variables
    - Plots and visualizations- patterns and trends found
    - exporting clean dataframe into a csv file to run in Models.ipynb notebooks. (CSV file is also saved in repository)
2. Modeling 1.ipynb- Decision Tree Classification
3. Modeling 2.ipynb- Support Vector Machine
4. Modeling 3.ipynb - K-nearest Neighbors


### References:
##### https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home
##### https://github.com/MengtingWan/goodreads/blob/master/README.md
- Citations:
    - Mengting Wan, Julian McAuley, "Item Recommendation on Monotonic Behavior Chains", in RecSys'18. [bibtex]
    - Mengting Wan, Rishabh Misra, Ndapa Nakashole, Julian McAuley, "Fine-Grained Spoiler Detection from Large-Scale Review Corpora", in ACL'19. [bibtex]

