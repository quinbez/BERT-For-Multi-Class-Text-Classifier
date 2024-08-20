# BERT-For-Multi-Class-Text-Classifier

## 📖  **Introduction** 
This project leverages BERT (Bidirectional Encoder Representations from Transformers) for text classification tasks. The goal is to classify text data into predefined categories using a fine-tuned BERT model. The project involves data preprocessing, model training, and evaluation on a dataset of consumer complaints.

## Project Structure
**Input**

- complaints.csv: The dataset containing consumer complaints. It should include a column with the text data and a column with the labels.

**Output**

- tokens.pkl: Pickle file containing the tokenized text data.
- labels.pkl: Pickle file containing the encoded labels.
- label_encoder.pkl: Pickle file containing the label encoder.
- bert_pre_trained.pth: The trained BERT model.

## 🔧 **Installation**
To get started, ensure you have the required libraries installed:

    * torch 
    * transformers 
    * scikit-learn 
    * pandas 
    * numpy 
    * tqdm
    
 ## 🔀  **Quickstart Guide**
1. Import Libraries
2. Set Hyperparameters
3. Load and Preprocess the Data
4. Save Processed Data
5. Define Custom Dataset
6. Build the BERT Classifier Model
7. Train the Model
8. Test the Model
9. Predict New Text

## 📂 **Project Link:** 
https://github.com/quinbez/BERT-For-Multi-Class-Text-Classifier/blob/main/BERT_for_Multi_class_text_classifier.ipynb
