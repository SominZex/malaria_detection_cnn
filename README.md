## Malaria Detection 

### The Model
The directory contains ipynb file of building and training a CNN model to diagnose Malaria parasites in the blood cell.  
The model detect and diagnose Malaria parasites Plasmodium falciparum (or P. falciparum) Plasmodium malariae (or P. malariae). 
The model was trained with 22000 different blood samples, 2700 Validation sample and 2700 test samples.

### Dataset Summary
27000 different opensource blood images are used in the process. 22000 images used for trainig, 2700 used for validation, 2700 used for testing.
Dataset not included in the directory.
Infected blood is marked 'P' and uninfected blood is marked 'U' in the validation section. (P = Parasitic | U = Uninfected) 

### Model Hyperparameter tuning
Model was tuned it's hyperparameter several times iteratively. No comments and markdown included in this step.

### Environment Setup
No local environment included in the directory. In case one wants to reuse the ipynb, setup up the virtual invironment by executing 'pip install -r requirements.txt' in the terminal.
All necessary packages are included in the 'requirements.txt' file.
