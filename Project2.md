# CS 167 Project 2

## Project Description:

Choose your own Machine Learning Adventure (Part II)

## Learning Objectives
For this project, you will conduct a machine learning experiment of your own design. Your final write-up should read like a lab report in which you explain what you built, what you observed, and how you interpreted the results. This directly addresses two course learning objectives stated in the syllabus:

- Students will be able to create software which utilizes machine learning programming libraries in order to conduct machine-learning-based data analysis.
- Students will be able to develop and conduct machine-learning-based data analysis experiments, and they will be able to interpret and explain the results.

## Project Description:
For this second project, you will choose **one of two structured project paths**:  
(1) a deep-learning image classification study, or  
(2) a custom transformer-based application of your choice.

You will be assessed on your ability to use the tools and algorithms introduced in this class. You are the machine learning engineer—your job is to design your experiments, justify your decisions, and draw meaningful conclusions from your results.

---

# Option 1 — Compare Neural Networks on Image Data

For this option, you will use one of the provided image datasets and implement **three models**:

- A Multilayer Perceptron (MLP)  
- A Convolutional Neural Network (CNN)  
- A fine-tuned AlexNet model  

Your task is to explore different configurations of each model, train them, and thoroughly compare and contrast their performance.

### Dataset Choices:
You may choose from one of the following datasets:

#### Image Classification (bfgmss) [recommended]
- Color 150×150 images  
- Six classes: building, forest, glacier, mountain, sea, street  
<p align="center">
  <img src="https://raw.githubusercontent.com/urness/CS167Fall2025/main/bfgmss_example.png" width="600">
</p>

 - Sample starter code provided [here](https://github.com/urness/CS167Fall2025/blob/main/project2startercodebfgmss.ipynb).

#### Chest X-Ray Pneumonia Detection (warning: difficult)
- Grayscale 200×200 images  
- Labels: NORMAL or PNEUMONIA
<p align="center">
  <img src="https://raw.githubusercontent.com/urness/CS167Fall2025/main/x_ray_example.png" width="600">
</p>

- Sample starter code provided [here](https://github.com/urness/CS167Fall2025/blob/main/project2startercodexray.ipynb).

Your report must explain *why* each model performed the way it did. Discuss architectural differences, suitability of the model to the dataset, and the impact of tuning decisions.

---

# Project Expectations:
Your final submission will be a **Kaggle iPython notebook** that includes your code, results, and written analysis. Most importantly, you will use text cells in the notebook to explain what you did, interpret the results, and make your recommendations.

Your written markdown sections must include the following:

### 1. Problem (2 points)
State the problem you are trying to solve. Include a description of the dataset, the classes involved, and your overall goal. Your project should read like a research report.

### 2. Research (10 points)
This is where your code and experiments go.

Your research must include:
- A clear description of the process you used  
- Parameter tuning efforts (not only running more epochs)  
- Graphs showing performance of each model  
- Appropriate evaluation metrics

### 3. Analysis (12 points)
Explain your findings in depth:
- Interpret the results. Describe what your experiments revealed. Narriate your findings.
- What is AlexNet?  
- Which model performed best, and why?
- Which model struggled, and why?  
- What insights or recommendations can you make?  
- How did you choose tuning parameters?  
- What did you find interesting or unexpected?

This section should be the most substantial part of your report and will be evaluated based on the depth and thoroughness of your analysis.

### 4. Bumps in the Road (1 point)
Briefly describe the challenges you encountered and how you addressed them.

---

# Option 2 — Do Something Interesting with Transformers

For this option, you will design a project involving **transformers**. This may include natural language processing, embeddings, retrieval-augmented generation, local LLMs, or creative transformer applications.

Possible ideas include:
- Building a **local chatbot** using Ollama and serving it through a simple Flask webpage  
- Creating a domain-specific assistant (e.g., math tutor, cybersecurity advice bot, study helper)  
- Fine-tuning a small transformer on a custom dataset  

If you choose this option, your report must include:
- The code you wrote  
- A clear user guide explaining how to run or use your system  
- Screenshots or example interactions demonstrating functionality
- Analysis of how transformers worked well in this project, as well as their shortcomings.

---

# Project Expectations:
Your final submission will be a **Google Colab notebook** and any supporting files needed to run your system.

Your write-up must include:
- Clear explanations of your approach  
- Code used in your application  
- Graphs, metrics, or demonstration outputs  
- Screenshots illustrating your application in action  

---

## Use of Generative AI (ChatGPT, Copilot, Gemini, etc.)

You may use generative AI tools for this project **as long as you clearly acknowledge it**.

1. **You must cite any AI assistance.**
  Include a short “AI Acknowledgment” at the top or bottom of your notebook describing what tools you used and how they contributed.

2. **You are responsible for understanding all code and explanations you submit.**
  You must be able to explain your own work. Your grade will be based on the quality of your analysis and reasoning — areas where generative AI often struggles to deliver at a high level.

3. **Uncited AI use is considered academic dishonesty.**
  If you use AI, you must acknowledge it. Failure to do so violates academic integrity expectations.
---

# Last Notes
- Make sure your name is at the top of your notebook.  
- Name your file `YOUR_LAST_NAME_Project2.ipynb` and submit via Blackboard.
