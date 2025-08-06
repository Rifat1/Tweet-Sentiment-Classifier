## Tweet Sentiment Classifier

## Objective

To build a PyTorch-based neural network that classifies tweets as either **Negative** or **Positive** in sentiment using the Sentiment140 dataset from kaggle.

---

## Technologies Used

- **Python**
- **PyTorch**
- **Pandas**, **NumPy**
- **scikit-learn**
- **Jupyter Notebook**

---

## My Role & Contributions

- Preprocessed a large CSV dataset (1.6M tweets) from kaggle, filtering for binary sentiment (negative vs positive).
- Implemented a basic feedforward neural network using PyTorch with Embedding and Linear layers.
- Handled tokenization, padding, and batching using custom PyTorch Dataset and DataLoader.
- Trained the model using `CrossEntropyLoss` and evaluated using classification metrics.

---

## Outcome

- Achieved ~80% precision, recall, and F1-score on both positive and negative tweets.
- Demonstrated effective use of PyTorch for natural language processing on a real-world dataset.
