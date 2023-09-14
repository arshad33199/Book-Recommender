# Book-recommender:

![david_williams_story_books_for_1649503107_9f6d37ba_progressive](https://github.com/arshad33199/Book-Recommender/assets/142779412/a060b464-b81a-4597-ada3-a71fdda0efbf)






## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Tools and Technologies used](#Approach)
* [Feature Selection](#Feature-Selection)
* [Exploratory data analysis](#Exploratory-data-analysis)
* [Data Preprocessing](#Data-Preprocessing)
* [Model Implementation](#Model-Implementation)
* [Recommender](#recommender)




## Problem Statement:
This is a Machine learning project.i am trying to build recommender for book.




## Tools and Technologies used:
  * Pandas : For loading the dataset and performing data wrangling.
  * Numpy: For some math operations
  * Matplotlib: For data visualization.
  * Seaborn : For data visualization.
  * ipywidgets: for interactive plots.
  
## Feature Selection:

In this section I am doing all the Data cleaning and analysis.Most of the data is in categorical form which should get converted.

Created a new column such as year with the help of publication_date.  

I did some feature engineering in it and encoding.There are many columns which i created from the existing column which you can see in the notebook.


## Exploratory data analysis:

Checked in which year how many books published.


Top 10 Authors with maximum book published.


![download](https://github.com/arshad33199/Book-Recommender/assets/142779412/fcc37116-4e5f-455f-ab9a-c4ffc995d8d0)


Checked how many languages books are available in the dataset.

Created distplot for average rating.

![download](https://github.com/arshad33199/Book-Recommender/assets/142779412/6cf99e85-b17a-4d6a-913e-1566e44929ce)



Top 10 publishers.


![download](https://github.com/arshad33199/Book-Recommender/assets/142779412/384e789a-89ff-4188-a6b6-7f1aa9a7b1a4)







## Data Preprocessing:

 Checked performed data type Correction and string formatting.



## Model Implementation:

I used kNN.
 
## Recommender:

i made different types of recommender such as Publisher, Authors, Language and Book Recommender.






