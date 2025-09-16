
# Laptop Product Review Classification using Deep Learning and NLP

This project aims to classify laptop product reviews into **positive** or **negative sentiment** using deep learning models such as **LSTM**, along with **text preprocessing and word embeddings**.

---

## Project Structure

- `Laptop_review_classification.ipynb` – Main notebook with all code steps.
- `Laptop_Review_Final_Dataset_With_Source.csv` – Cleaned + synthetic dataset with labels and source info.
- `README.md` – Instructions to run the project and setup environment.

---

## Libraries & Dependencies

Make sure to install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk keras tensorflow
```

### Python Version
- Python 3.7 or higher

---

## How to Run the Notebook

1. **Open in Google Colab or Jupyter Notebook.**

2. **Upload the dataset file:**
   - `Laptop_Review_Final_Dataset_With_Source.csv`

3. **Run the cells step by step:**
   - Data loading
   - EDA & preprocessing
   - Tokenization and padding
   - LSTM model building and training
   - Evaluation (accuracy, precision, recall, F1-score)

---

## Models Used

- **Embedding Layer** for vectorizing words
- **LSTM (Long Short-Term Memory)** for capturing context in sequential text
- Output through **Dense Layer with Sigmoid** activation

---

## Dataset Notes

- The original dataset had duplicate reviews, which were removed.
- 10 additional synthetic reviews were manually created (5 positive, 5 negative) to balance the dataset.
- Each row has a `Source` column indicating if the review is `Original` or `Synthetic`.

---

## Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**
