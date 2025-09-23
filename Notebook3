# Notebook #3: Cross Validation with kNN and Vehicle Cost

## The Data: :fuelpump:
For this notebook, you're going to continue working with the k-NN function you made for predicting vehicle fuel efficiency from Notebook 2. As with Notebook 2, use only the data with `'fuelType' == 'Regular'` and use the features `["comb08","year", "cylinders", "displ"]` with "comb08" being the target feature.

However, this time, you are going to **cross-validate** your model by using independent training and test subsets of the data. 

For an example of this using the Iris dataset, see the notes from Lecture 07, ([or this GitHub repository](https://github.com/merriekay/CS167Code/blob/main/Day07_Notes.ipynb))

## What you need to do: 
1. Note that you will need to do some things to adapt it to your problem:

    - Don't forget that you are doing regression-- pay attention to what you need to change to make this do regression rather than classification.
    - Make sure to implement an appropriate regression metric - you can use any of the ones we talked about, but code it up yourself. 
    - The sample code uses the word "classification" a lot in names of things - make sure you use the word "regression" instead if you write similar functions.

2.  Use the approximately the first 500 rows in the shuffled set as testing data. Feel free to use fewer examples in your testing set -- particularly if it takes a long time to run on your computer (e.g. more than 30 seconds). 
3. Test your model using several different values of k and **graphically show the results**.
4. Run this for several different splits of the data -- varying the number of elements in the testing data and/or different values for the "random_state". 
5. What conclusions can you draw about the best number for k for the k-NN algorithm for this data set? Use a markdown cell to explain your conclusions in a few sentences.
