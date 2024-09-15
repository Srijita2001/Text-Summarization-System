# Text Summarization System


Overview

This project implements a text summarization system using the DistilBART model. The system fine-tunes the BART model on a custom dataset containing paragraphs and their corresponding summaries. The model can then generate concise summaries for user-provided text.



Project Structure

•	data/: Contains the CSV file with the dataset (summary.csv).

•	src/: Contains the main Python code for training the model, preprocessing data, and generating summaries.

•	requirements.txt: Lists the dependencies required for the project.


Dependencies

•	Install the required libraries using the following command:

pip install -r requirements.txt



Dataset

The dataset should be a CSV file with the following columns:

•	Paragraph

•	Summary


Usage

1.	Prepare the Dataset: Ensure your dataset is in a CSV file with columns Paragraph and Summary.
2.	Training the Model:
   
   o	The code will load and preprocess the dataset.
   
   o	It will then fine-tune the DistilBART model with the provided dataset.

3.	Generating Summaries:
   
o	You can generate summaries for any input text using the trained model.


Training Parameters
•	Epochs: 50
•	Batch Size: 8
•	Learning Rate: 2e-5


Acknowledgements
•	Hugging Face Transformers library for providing the BART model and utilities.
•	PyTorch for the deep learning framework.

