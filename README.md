# Sentiment-Analysis
Finetuning bert base cased model to perform sentiment analysis on sst2 dataset

In this project, bert base cased classifier was finetuned on the training dataset of the setfit sst2 (from Huggingface) and then finally accuracy was observed on the test dataset. 90.2% accuracy was achieved.

Tokenizer used was imported from autotokenizers for the bert base cased model and then data collation was done with padding using the tokenizer.

The model was then finetuned by training on the dataset while wandb was used to plot the accuracy and loss graphs on the training and validation datasets.

Model was then tested on the test dataset and the accuracy was calculated based on the number of correct and incorrect predictions made as compared to the expected label.

The incorrect predictions were annotated and I tried to figure out why the incorrect classification could have happened.

This project was done as part of coursework for CSCI 5541- Natural Language Processing in Spring 2024. Parts of the code were provided by the professor as part of the coursework.
