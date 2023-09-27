# Hindi Text Sentiment Classification model

This repo aims on fine tuning Google's **MURIL** model for the down stream task of sentiment classification. Th*e original model was trained on English, Hindi and many other languages and in this repo its base architecture is used. 

## Files

For training the model, first create a python3 virtual environment using the code `python3 -m venv <environment_name>`. The activate the environment using `source <environment_name>/bin/activate` for linux users and for windows users use the command `<environment_name\Scripts\activate>`. After activating the environment, download all the packages from the `requirements.txt` file using the command `pip install -r requirements.txt`. 

There is a `ipynb` file which contains the code for fine tuning the model on the given dataset using Hugging Face Transformers and Tensorflow. Run all the cells sequentially for training the model and saving it to the directory. After the model is saved it can be used to classify any piece of hindi text to one of the three classes **positive**, **neutral** and **negative**. 

More information on the original model Google Muril can be found [here](https://huggingface.co/google/muril-base-cased). 
 