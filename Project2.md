# CS 167 — Project 2
## Choose Your Own Machine Learning Adventure

## Learning Objectives
In this project, you will design and conduct a machine learning experiment of your choosing. Your final write-up should read like a lab report: clearly explaining what you did, presenting your results, and interpreting what those results mean.

This project directly addresses two course learning objectives:

- Students will be able to create software that uses machine learning libraries to perform data analysis.
- Students will be able to design, conduct, interpret, and explain machine-learning-based experiments.

---

# Project Overview
You will be evaluated on your ability to use the algorithms and tools introduced in this course. Below are the two project paths you may choose from. Regardless of the option selected, your job is to behave like a machine learning engineer: run meaningful experiments, analyze the results, and draw clear conclusions.

---

# Option 1 — Compare MLPs, CNNs, and a Fine-Tuned AlexNet on Image Data

Choose one of the following datasets, then implement **three models**:
1. An MLP  
2. A CNN  
3. A fine-tuned AlexNet  

Your task is to explore multiple configurations, run experiments, and thoroughly compare model performance.

## Available Datasets

### Chest X-Ray Pneumonia Detection
- Grayscale 200×200 images  
- Labels: NORMAL or PNEUMONIA  
- Sample code provided (uploading to Kaggle, starter MLP/CNN classes)

### Image Classification (bfgmss)
- Color 150×150 images  
- Six classes: building, forest, glacier, mountain, sea, street  
- Sample code provided (uploading to Kaggle, starter MLP/CNN classes)

In your report, explain why each model performed the way it did. Discuss architecture differences, suitability for the data, and the impact of hyperparameters.

---

# Project Expectations (for Option 1)
Your final submission will be a **Kaggle iPython notebook** containing:
- All code used  
- All graphs, outputs, and results  
- Clear, well-written markdown explanations  

Your write-up must include the following sections:

### 1. Problem (2 points)
Clearly state the problem you are trying to solve and the goal of your experiment.

### 2. Research (10 points)
This section includes your code, experiments, and model exploration.

Your research section must include:
- A description of the process you followed  
- Parameter tuning efforts (not just running for more epochs)  
- Graphs showing model performance  
- Metrics appropriate to your task (e.g., accuracy)

### 3. Analysis (12 points)
Explain your findings in depth:
- What did you discover?  
- Which model performed best, and why?  
- Which models struggled, and why?  
- What insights or recommendations do you have?  
- How did you decide how long to train or tune the model?

This should be the most substantial and thoughtful part of your report.

### 4. Bumps in the Road (1 point)
Briefly describe challenges you encountered:
- What went wrong?  
- How did you fix it or work around it?

---

# Option 2 — Do Something Interesting with Transformers

Choose this option if you'd like to explore cutting-edge AI by building a project involving **transformers**.

Possible project ideas include:
- Building a local chatbot using Ollama and hosting it through a simple Flask webpage  
- Creating a domain-specific assistant (e.g., math tutor, cybersecurity helper, study guide generator)  
- Fine-tuning a small transformer model on a custom dataset  

If you choose this option, your report must include:
- The code you wrote  
- A user guide explaining how to use your system  
- Screenshots and examples demonstrating your working application  

---

# Project Expectations (for Option 2)
Your final submission will be a **Google Colab notebook** and supporting documents containing:
- All code used  
- All graphs, outputs, and results  
- Clear, well-written markdown explanations  
- Screenshots and example interactions demonstrating your system  

---

# Use of Generative AI (ChatGPT, Copilot, Gemini, etc.)

You may use generative AI tools for this project, under the following conditions:

1. **You must clearly cite any AI assistance.**  
   Include an “AI Acknowledgment” section in your notebook.  
   Example:  
   *Portions of this code and/or text were generated with the assistance of ChatGPT (OpenAI) on 11/25/2025 and then modified by me.*

2. **You are fully responsible for understanding all code and analysis you submit.**  
   You must be able to explain:  
   - What the code does  
   - Why it is appropriate for the task  
   - How the results should be interpreted  

3. **Code suspected to be purely AI-generated (without understanding) will be scrutinized.**  
   In such cases, your analysis and explanations will be held to the highest standards.

4. **Uncited AI use is treated as academic dishonesty.**

---

# Final Notes
- Put your name at the top of your notebook.  
- Save your file as `YOUR_LAST_NAME_Project2.ipynb`.  
- Submit your notebook on Blackboard.
