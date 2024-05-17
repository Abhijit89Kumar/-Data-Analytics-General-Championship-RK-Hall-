Data Analytics General Championship - RK Hall
This repository houses Jupyter notebooks and resources for advanced data analysis and machine learning tasks, including clustering, model fine-tuning, and a web application demo.

Folder Structure
Notebook 1:
Clustering Algorithms: Implements K-Means, Gaussian Mixture Model (GMM), DBSCAN, and HDBSCAN. Requires Final_hopefully.csv and Unclustered_Demographic.csv in the working directory.
Required Files: Contains essential files like final_hopefully.csv, Social.csv, and the imputing_fxn.ipynb notebook for data preprocessing.
For164 Zips-20240315T132840Z-001: Additional data files for analysis.
Notebook 2:
Fine-Tuning: Fine-tunes Mistral 7B and Gemma 2B models on LLm_on_10k_train.csv. Fine-tunes a BERT model on filtered_health_data.csv for resource connection tasks.
Required Files: Includes the necessary data files for fine-tuning.
Web-app Screenshots: Contains screenshots of the web application usage.
Demo: A video demonstration of the web application.
Output: A CSV file with sample inputs and corresponding outputs from the model.
Setup Instructions
Hugging Face Access:

Create a Hugging Face account.
Generate a read access token under Settings -> Access Tokens.
Create an environment variable named HF_READ_TOKEN and store the token value.
Grant your notebook access to this environment variable.
Model Weights:

Download the following fine-tuned model weights and configurations from the provided dataset folders:
model_llama2: 7B llama2 chathf model
model_gemma: 2B gemma instruct model
model_mistral: 7B mistral instruct model
Place these folders within your Python environment.
Data Files:

Ensure all required CSV files are uploaded to the correct working directories as specified in each notebook's instructions.
Hardware Requirements
Minimum: A GPU with at least 50GB of VRAM is recommended for optimal performance.
Alternative: If your GPU has less VRAM, you can load the models onto the CPU, but expect slower processing times.
Important Note: This repository is designed for advanced users familiar with data analytics, machine learning, and model fine-tuning.  Please ensure you have the necessary technical knowledge and resources before proceeding.
