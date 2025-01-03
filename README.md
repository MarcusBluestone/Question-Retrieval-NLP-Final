# NLP Question Retrieval
[`overview.pdf`](overview.pdf) contains the final version of our paper

Our code was created to be run in Google Colab. “balanced_df.csv” is the General dataset. “tech_data.csv” is the Technology dataset.

The cell in the beginning of the notebook is for mounting the drive and importing the data.

After these first few data cells, we have the analysis code. These cells can be run to re-produce our results. The order is as follows:

- Bow with TF-IDF

- Pre-Trained CBoW (Word2Vec)

- Our own CBoW (Word2Vec)

- Binary Classification with BERT Pre-trained

- Binary Classification with BERT Fine-Tuned

- BERT CLS Token Approach

- BERT CLS Token Approach Fine-Tuned

Each method has a subsection for the tech and general datasets.

The GoogleNews weights can be found at: https://drive.google.com/file/d/1j7-0mg_xw7FWES12AA0rAXOTUHt-NcDJ/view?usp=sharing
