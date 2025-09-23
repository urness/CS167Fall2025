# Notebook #3: Cross Validation with kNN

For this notebook, you're going to continue working with the k-NN function, but applied to a new dataset -- predicting the price of used cars. :articulated_lorry: :red_car: :taxi: :bus:

## The Data: :blue_car:

For this notebook, you should first download the dataset `Car_Price_Prediction.csv` - available on blackboard.  
You need to only use the numeric features `['Engine Size', 'Mileage', 'Year', "Price"]` with `"Price"` being the target feature.

In this Notebook, you are asked to **cross-validate** your model by using independent training and test subsets of the data. 

For an example of this using the Iris dataset, see the notes from September 18th, ([or this GitHub repository](https://github.com/urness/CS167Fall2025/blob/main/Day08_Metrics_and_Testing.ipynb))

## What you need to do: 
1. Put your name at the top of your .ipynb file.
2. Download `Car_Price_Prediction.csv` from the blackboard website, and create a subset of the data that consists of the numeric features `['Engine Size', 'Mileage', 'Year']` along with "Price", the target feature. Prepare the data and kNN functions in the following ways:
    - Clean the data. Are there any missing data? Use a text field to describe what you decided to do to clean the data and why.
    - Don't forget that you are doing regression -- pay attention to what you may need to change in the implementation of kNN to make this do *regression* rather than *classification*.
3. Use the approximately 20% of a shuffled set as testing data. 
4. Test your model using several different values of k and **graphically show the results**.
    - Make sure to implement an appropriate regression metric - you can use any of the ones we discussed in class. 
    - The sample code (with the iris dataset) uses the word "classification" a lot in names of things - make sure you use the word "regression" instead if you write similar functions.
5. What conclusions can you draw about the best number for k for the k-NN algorithm for this data set? Use a markdown cell to explain your conclusions in a few sentences.
6. Do something original with the data. Ask a question. Get an answer. Explain your thinking and your results.

To submit your work, use a Markup cell to put your name at the top of the file. Download the .ipynb file. Submit this assignment on Blackboard.
