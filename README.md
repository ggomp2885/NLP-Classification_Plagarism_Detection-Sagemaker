# Plagiarism Project, Machine Learning Deployment
## Project Overview
In this project I build a Classification Model which uses NLP preprocessing techniques for detecting the level of plagarism in newly submitted documents. I use 3 notebooks to accomplish this task, separated by the steps. Notebook 1 explores the data and its distribution, Notebook 2 is for the text preprocessing techniques, Notebook 3 contains the code for training the SKLearn model. Comments are included in each of the notebooks to explain each step as it is run.  This project is also built to be fully deployable for production use in a web app!

Link to Plagiarism Dataset:
https://s3.amazonaws.com/video.udacity-data.com/topher/2019/January/5c4147f9_data/data.zip

### Files in this repository and their purpose
#### Folders

   source_sklearn - Folder containing the train.py file for the Sklearn model parameters
  

#### Files

   1_Data_Exploration.ipynb - Notebook containing all data exploration steps

   2_Plagiarism_Feature_Engineering.ipynb - Notebook containing all feature engineering steps
   
   3_Training_a_Model.ipynb - Notebook containing all model training stesp
   
   helpers.py - Contains functions to aid in the preprocessing of the text data
   
   problem_unittests.py - Contains functions to run unit test checks throughout the notebook
   
   LICENSE - MIT license for this project

   README - this file


### Main Notebook uses Python 3.6, and the following libraries
   Pandas

   Matplotlib

   SKlearn

   Numpy
