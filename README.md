# -Data-Analytics-General-Championship-RK-Hall-
﻿Folder:Notebook 1

(All resources mentioned below are present in the Notebook1_contents folder provided in the zip folder. Select path according to model and dataset path)

* Create an account on Huggingface and then go to Huggingface->Settings->Access Tokens and then create a read token , copy its value , create a secret key preferably named “HF_READ_TOKEN” in your environment and add the value of the token.
Finally grant access notebook access to the created secret key.
* Download weights and biases of fine-tuned models and upload them in separate folders in your python environment from the dataset folders provided as follows:
* 'model_llama2' - Contains the safetensor and model configuration files for the 7B llama2 chathf model
* 'model_gemma' - Contains the safetensor and model configuration files for the 2B gemma instruct model
* 'model_mistral' - Contains the safetensor and model configuration files for the 7B mistral instruct model
* Upload the csv files needed for the input imputing function to work 
* -final_hopefully.csv(Available in the 'Required Files' folder inside the 'Notebook_1' folder)
* -Social.csv(Available in the 'Required Files' folder inside the 'Notebook_1' folder)
* Upload the imputing function notebook imputing_fxn.ipynb before running it.

Clustering Algorithms Part of the 'Notebook_1'
This repository contains implementations of several clustering algorithms within a Jupyter notebook, designed to explore and analyze data through various clustering techniques. The implemented algorithms include:
* K-Means Algorithm
* Gaussian Mixture Model (GMM) 
* Density-Based Spatial Clustering of Applications with Noise (DBSCAN) 
* Hierarchical Density-Based Spatial Clustering of Applications with Noise (HDBSCAN)
For the clustering notebook to function correctly, please ensure the following CSV files are uploaded to the working directory:
* Final_hopefully.csv - primary dataset intended for clustering analysis.
* Unclustered_Demographic.csv - A dataset containing demographic information

** In 'Notebook_1' there is a file in 'Required Files','For164 Zips-20240315T132840Z-001'.

Folder:Notebook 2

Notebook 2 includes the Imputeing function code , fine-tuning of the Mistral 7b(instruct) and Gemma 2b(instruct) models on'LLm_on_10k_train.csv', and BERT fine-tuning on 'filtered_health_data.csv' for the 'Connecting People with Resources' task. 

The files 'LLm_on_10k_train.csv' and 'filtered_health_data.csv' have been provided in a folder named 'Required Files' in the 'Notebook_2'


Folder:Web-app Screenshots
This folder contains the screenshot of the different stages of the Web-app usage.


'Demo': This video shows the whole process of the Web-app usage.


'Output': This is a csv file containing sets of inputs with their repective outputs.

Minimum Notebook Requirements:- Atleast 50GB GPU vRAM.(If less vRAM is available then load the models in CPU)
