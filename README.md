Semantic Textual Similarity Using BERT

Introduction:
This project aims to demonstrate how to perform Semantic Textual Similarity using BERT (Bidirectional Encoder Representations from Transformers), a state-of-the-art pre-trained natural language processing model by Google. In this project, we will fine-tune BERT on the Quora Question Pair dataset.

Dataset:
We used the Quora Question Pair dataset for fine-tuning BERT. This dataset consists of question pairs with a label indicating whether the questions are semantically equivalent or not. 

Requirements:
To run the code, the following libraries need to be installed:

- tensorflow==2.5.0
- transformers==4.6.1
- pandas==1.2.4
- numpy==1.19.5
- scikit-learn==0.24.2

Fine-tuning BERT:
We fine-tuned the BERT model using the transformers library in Python. The code for fine-tuning the model is provided in the file "mm.ipynb". The script loads the Quora Question Pair dataset and fine-tunes the BERT model on the task of semantic textual similarity. 

Conclusion:
This project demonstrates how to perform Semantic Textual Similarity using BERT. By fine-tuning the BERT model on the Quora Question Pair dataset, we can achieve good performance on the task of determining semantic similarity between two text inputs. This technique can be applied to a wide range of natural language processing tasks, such as sentiment analysis, question answering, and text classification.
