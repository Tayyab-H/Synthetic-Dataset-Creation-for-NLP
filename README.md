# Synthetic-Dataset-Creation-for-NLP

Using the power of word2vec, the notebooks showcase how to create synthetic NLP data for classification from a very small basic balanced manually inputted dataset. It is capable of expanding an NLP dataset of only 30 samples to one of over 1000 samples. This is powerful for specific NLP tasks. A copy of the paper is included in the repository. I highly recommend reading it before proceeding as it gives context for the project.

Install all dependancies using:
```
pip install -r requirements.txt
```

OR 

Run the first cells in each ipynb notebook.

Run the dataset creation notebook using whichever notebook program you prefer (I used Jupyter-lab but vscode, google colab work equally well).
Run the Dataset Creation with:

```jupyter-lab DatasetCreation.ipynb ```

The pretrained google word2vec is not included in the git repository due to size. The dataset creation notebook contains a download to the pretrained amazon word2vec model used to test this project.  

First run the dataset Creation notebook. Then go through the training notebook.
