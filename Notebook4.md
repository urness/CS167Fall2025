# Notebook #4: Scikit-Learn with the Wine Quality Dataset  

In this notebook, you will explore how to use the [scikit-learn](https://scikit-learn.org) library to perform machine learning experiments.  

## 📊 The Data  

We will work with a new dataset focused on **wine quality** 🍷. The dataset is available in the **“Datasets”** section of Blackboard (winequality-white.csv). The data does not need to be cleaned. 

The original source can be found on [Kaggle: White Wine Quality Dataset](https://www.kaggle.com/datasets/piyushagni5/white-wine-quality).  

The goal for this machine learning exercise is to use the scikit-learn library implementation of **k-Nearest-Neighbors** and **Decision Trees** to make predictions on the quality of wine based on the learning examples. 
## The Exercises  

**Part 1: [2 points]**  
Run at least **six variations** of the algorithms and evaluate their performance using an appropriate regression metric (e.g., Mean Squared Error, Mean Absolute Error, R²). Use scikit-learn modules. Your comparison should include:  
- k-Nearest Neighbors with a **small value of k**  
- k-Nearest Neighbors with a **large value of k**  
- Weighted k-Nearest Neighbors with the **same small k** as above  
- Weighted k-Nearest Neighbors with the **same large k** as above  
- A Decision Tree with **default parameters** (you may set `random_state` to ensure reproducibility)  
- A Decision Tree with at least one **tuned parameter** that results in a smaller tree (e.g., `max_depth`, `max_leaf_nodes`)  

---

**Part 2: [1 point]**  
Normalize the data using `StandardScaler` from scikit-learn. Then, run a **weighted k-Nearest Neighbors** model and adjust the number of neighbors (`k`) to maximize performance.  

---

**Part 3: [2 points]**  
In a Markdown cell, answer the following reflection questions:  
- What effect did using a large k vs. a small k have on your results?  
- Which algorithm performed better overall: kNN or Decision Trees? Why do you think that was the case?  
- What effect did normalizing the data have on your results? Why might normalization influence performance?  

---

**Part 4: [1 point]**  
Do something **original** with the dataset. Ask a new question, run an experiment, and explain your reasoning and results. Creativity and thoughtful analysis are encouraged.  
