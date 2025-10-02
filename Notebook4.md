# Notebook #4: Scikit Learn with Wine Quality Dataset

For this notebook, you are going to demonstrate how to use the scikit-learn library (https://scikit-learn.org) to perform machine learning experiments. 
## The Data :bar_chart: 
You will use a new dataset that deals with wine quality :wine_glass: (available in the "Datasets" section of the blackboard website). The data is originally from kaggle.com[https://www.kaggle.com/datasets/piyushagni5/white-wine-quality]

The goal for this machine learning exercise is to use the scikit-learn library implementation of **k-Nearest-Neighbors** and **Decision Trees** to make predictions on the quality of wine based on 1599 learning examples. 

## The Exercises:
**Part 1: [2 points]** You must run at least 6 variations of the algorithms and display their results using an appropriate regression metric (again, use the scikit-learn modules). I will be looking for the following to be included in your comparison:
* k-Nearest-Neighbor with a small value of k
* k-Nearest-Neighbor with a large value of k
* weighted k-Nearest-Neighbor with a small value of k (the same one you used for the unweighted version)
* weighted k-Nearest-Neighbor with a large value of k (the same one you used for the unweighted version)
* a decision tree with default parameter values (you can establish `random_state=` to keep your executions consistent)
* a decision tree, setting some kind of parameter that results in a smaller tree 

**Part 2: [1 point]** Normalize the data and run a weighted k-Nearest-Neighbor algorithm on it (use the StandardScalar from sklearn). Adjust the number of k to maximize the performance.

**Part 3: [2 points]** Use a Markup cell to answer the following questions:
* What effect did a large k vs. a smaller k have on your results?
* What algorithm performed better? kNN or Decision Trees? Why do you think this was the case?
* What effect did normalizing the data have on your results? Why do you think this was the case? 

**Part 4: [1 point]** Do something original with the data. Ask a question. Get an answer. Explain your thinking and your results.

Lastly, as always, use a Markup cell to put your name at the top of the file. Rename your file LastnameNotebook4.ipynb and submit it to this submission form. You do not need to submit a copy of the data.
