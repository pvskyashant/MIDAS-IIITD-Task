# MIDAS-IIITD-Task-3
IIITD Summer Internship 2021 Selection Task

Used the Jupyter notebook to execute task.

Required Libraries are imported 
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

The dataset is converted into csv file and is loaded
cs=pd.read_csv("flipkart_com-ecommerce_sample - flipkart_com-ecommerce_sample - flipkart_com-ecommerce_sample.csv")

Used the Tfidf Vectorization with Naive Bayes Model to fit the data
The accuracy obtained is arround 78%
I suppose the accuracy can also be increased with the Support Vector Machines model(SVM).
I would also be interested in knowing and implementing through SVM's.

Tfidf Vectorization assigns a score to a word based on its occurrence in a particular document, multiplying the term frequency of a word by the inverse document frequency will increase accuracy.

Naive bayes model then uses this data to predict using the MultinomialNB() function.

Visualization of the data is done using the plotly.express, it is first installed and imported into the workspace. Scatter plot is used to visualize the category and pid values.
I have also reffered to some resources like plotly, sklearn, geeks for geeks, stack abuse.com etc.
