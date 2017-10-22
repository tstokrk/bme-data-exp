# bme-data-exp
Biomedical engineering - miniproject - data exploration

## Project Overview

Welcome to the Data Exploration miniproject. You will learn how to clean and prepare data and build a pipeline that can be used for further exploration. The goal is that by completing this lab, you understand the first stage of data processing pipeline.

## Project Instructions

0. (Optional step) Fork the repository to your githab account. It allows you to upload the changes to your own github

1. Clean all the previous copies of this repo (it could be downloaded by other students).

```	
cd
ls -all
rm -rf bme-*
```

2. Clone the repository to your local PC

Go to your home directory, and clone the repository. In case you made a copy (fork) provide your own URL

```	
cd
git clone https://github.com/tstokrk/bme-data-exp.git
cd bme-data-exp
```

3. Create a new conda environment (it provide the necessary Python packages)
	
All necessary packages are listed in requirements.yml file.
  
Before you create the new env using conda, check if there is no different env with the same name on your PC.
  
```
conda env list
```

Remove all env that can create a conflict with the new one

```
conda env remove --name [name]
```
  
Create the new env using the package list from the provided file
	
```
conda env create -f requirements.yml
source activate data-exp
```
  
 If you want to create the new env with the specific NAME
 
 ```
conda env create -n NAME -f requirements.yml 
source activate NAME
```

4. Open the Jupyter Notebook and follow the instructions
	
```
jupyter notebook data_exp_numpy.ipynb
```
  
5. (Optional step) Commit and push all the changes to your own github repo 

```
git commit -m "My update.."
git push origin master
```
