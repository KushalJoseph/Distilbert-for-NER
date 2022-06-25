# Distilbert-for-NER
## Using a larger BERT-based model for the NER task, this project "distils" the knowledge into a smaller model, thereby providing similar accuracy levels, but fewer model parameters

Please go through the ipynb notebook for more information

Note:
Libraries to be installed
Run the following lines of code in the python notebook:

!pip install transformers datasets – upgrade
!pip install seqeval
!pip install optuna       # If you want to run our hyperparameter tuning code

To run the model, you need to have a hugging face token. To have a hugging face token, you need to create an account with the hugging face website, generate a new token, set it to “write” and put the token where prompted in the python notebook. 
While running the notebook, you will be prompted at a cell to do the above token verification. 
