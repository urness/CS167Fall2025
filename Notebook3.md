# Notebook #3: Cross Validation with kNN and Vehicle Fuel Efficiency

## The Data: :blue_car:
For this notebook, you will once again load a new data set dealing with cars :articulated_lorry: :red_car: :taxi: :bus: but with the target variable **Price** :heavy_dollar_sign: (Car_Price_Prediction.csv - available on blackboard).

For this notebook, you're going to continue working with the k-NN function you made for predicting vehicle fuel efficiency from Notebook 2. With this dataset, however, you need to only use the numeric features `['Engine Size', 'Mileage', 'Year']` with "Price" being the target feature.

However, this time, you are going to **cross-validate** your model by using independent training and test subsets of the data. 

For an example of this using the Iris dataset, see the notes from September 18th, ([or this GitHub repository](https://github.com/urness/CS167Fall2025/blob/main/Day08_Metrics_and_Testing.ipynb))

## What you need to do: 
1. Note that you will need to do some things to adapt it to your problem:

    - Don't forget that you are doing regression -- pay attention to what you need to change to make this do regression rather than classification.
    - Clean the data. Are there any missing data? Use a text field to describe what you decided to do to clean the data and why.
    - Make sure to implement an appropriate regression metric - you can use any of the ones we talked about, but code it up yourself. 
    - The sample code uses the word "classification" a lot in names of things - make sure you use the word "regression" instead if you write similar functions.

2. Use the approximately 20% of a shuffled set as testing data. Feel free to use fewer examples in your testing set -- particularly if it takes a long time to run on your computer (e.g. more than 30 seconds). 
3. Test your model using several different values of k and **graphically show the results**.
4. Run this for several different splits of the data -- varying the number of elements in the testing data and/or different values for the "random_state". 
5. What conclusions can you draw about the best number for k for the k-NN algorithm for this data set? Use a markdown cell to explain your conclusions in a few sentences.
6. Do something original with the data. Ask a question. Get an answer. Explain your thinking and your results.

To submit your work, use a Markup cell to put your name at the top of the file. Download the .ipynb file. Submit this assignment on Blackboard.
