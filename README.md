# Classifying Cancerous Brain Tumors 
This repository contains code and relevant materials for accomplishing the overall project goal: develop a convolutional neural network (CNN) or other classification model that achieves at least 85% recall when classifying glioma brain tumors. 

## Content Overview 
* Project Mission.pdf: introduces project motivation and goal.
* Brain Tumor Detection using CNNs.pdf: article detailing brain tumor detection using transfer learning methods and a 3-layer CNN.
* Rubric.pdf: provides the purpose, task, and criteria by which your efforts will be evaluated.
* SCRIPTS: contains code for pre-processing and preparing the data and code for evaluating classification models. 


## Process 
### Data Estalishment and Pre-processing 
1. Navigate to the data source website: <https://figshare.com/articles/dataset/brain_tumor_dataset/1512427?file=3381290>
2. Download all folders beginning with 'brainTumorDataPublic_' to your local machine.
3. Run the 1_preprocessing.ipynb file in the SCRIPTS folder. *Note:* You will need to modify the file paths for where the data is being read in from based on where it's stored on your local machine. You will also need to modify the output directory (where the data will be stored after processing).

### Data Preparation 
1. Run the 2_data_prep.ipynb file in the SCRIPTS folder. This file contains code to prepare the data for analysis (including splitting the data into training, validation, and testing sets). After running this file, you will be ready to begin building a convolutional neural network (CNN) or other model of your choosing! 

### Model Evaluation 
1. After fitting and tuning your models, evaluate your models by running the code in 3_model_eval.ipynb in the SCRIPTS folder. *Note:* You will need to add this chunk of code to the bottom of your analysis code. When the model has classified glioma tumors with at least 85% recall, you have achieved your goal! 
