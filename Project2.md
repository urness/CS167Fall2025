# CS 167 — Project 2
## Choose Your Own Machine Learning Adventure

## Learning Objectives 📝
In this project, you will design and conduct a machine learning experiment of your choosing. Your final write-up should read like a lab report: clearly explaining what you did, presenting your results, and interpreting what those results mean.

This project directly addresses two course learning objectives:

- Students will be able to create software that uses machine learning libraries to perform data analysis.
- Students will be able to design, conduct, interpret, and explain machine-learning-based experiments.

---

# Project Overview
You will be evaluated on your ability to use the algorithms and tools introduced in this course. Below are the two project paths you may choose from. Regardless of the option selected, your job is to behave like a machine learning engineer: run meaningful experiments, analyze the results, and draw clear conclusions.

---

# Option 1 — Do Something Interesting with Transformers

Interested in cutting-edge AI? Choose this option to create a project involving **transformers**.

Possible ideas include (but are not limited to):
- Build a **local chatbot** using **Ollama** and host it through a simple **Flask webpage**.
- Create a domain-specific assistant (e.g., a math tutor, cybersecurity advice bot, study helper, etc.).
- Fine-tune a small transformer on a custom dataset.

If you choose this option, your report must include:
- The code you wrote.
- A **user guide** explaining how to use your system.
- **Screenshots and examples** demonstrating your working application.

---

# Option 2 — Compare MLPs, CNNs, and a Fine-Tuned AlexNet on Image Data

Choose one of the following datasets, then implement **three models**:
1. An MLP  
2. A CNN  
3. A fine-tuned AlexNet  

Your task is to explore multiple configurations, run experiments, and deeply compare model performance.

## Available Datasets

### 🔹 Chest X-Ray Pneumonia Detection
- Grayscale 200×200 images  
- Labels: **NORMAL** or **PNEUMONIA**  
- Sample code provided (uploading to Kaggle, starter MLP/CNN classes)

### 🔹 Image Classification (bfgmss)
- Six classes: **building, forest, glacier, mountain, sea, street**
- Color images, 150×150
- Sample code provided (uploading to Kaggle, starter MLP/CNN classes)

**In your report, explain *why* each model performed the way it did.**
Discuss architecture differences, suitability for the data, and the impact of hyperparameters.

---

# Project Expectations ☑️
Your final submission will be a **Google Colab notebook** containing:
- All code used
- All graphs, outputs, and results
- Clear, well-written markdown explanations

Your write-up must include the following sections:

---

### 1. Problem (2 points)
Clearly state the problem you are trying to solve and the goal of your experiment.

---

### 2. Research (10 points)
This is where your **code**, **experiments**, and **model exploration** go.

Your research section must include:
- A description of the process you followed
- Hyperparameter tuning efforts
- Graphs showing model performance
- Metrics appropriate to your task (accuracy, loss, precision/recall, etc.)

---

### 3. Analysis (12 points)
Explain your findings in depth:
- What did you discover?
- Which model performed best?
- Which models struggled, and why?
- What insights or recommendations do you have?
- How did you decide how long to train/tune the model?
- Why did you stop tuning when you did?

This should be the **richest** and most thoughtful part of your report.

---

### 4. Bumps in the Road (1 point)
Briefly describe your challenges:
- What went wrong?
- How did you fix it or work around it?

---

# Final Notes
- Put **your name** at the top of your notebook.
- Save your file as **YOUR_LAST_NAME_Project2.ipynb**.
- Submit your notebook on **Blackboard**.
