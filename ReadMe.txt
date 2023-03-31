# Dataset Preparation
First of all create the train test data from the given csv files with the help of "dataset_preparation.py". After that if you want to add knowledge graph then use the generated json files in the "introducing_kg_in_dataset.py".

# For training 
There are three different model(seq2seq LSTM, DialoGPT, BART) to train, please change the pre-processed dataset accordingly.

# Dependencies requirements
tensorflow==2.8.2<br>
tensorflow-text==2.6.0<br>
spacy==3.4.1<br>
tensorflow-hub== 0.12.0<br>
transformers==2.9.0<br>
torch==1.12.1<br>
simpletransformers==0.63.7<br>
tensorflow-hub==0.12.0
