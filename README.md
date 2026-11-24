# App Review Rating Classification

Sentiment classification of Google Play app reviews with ML, RNNs and BERT.

## What it does

Classifies app reviews as Negative, Neutral or Positive. Compares TF-IDF models, RNN/LSTM/GRU networks and a fine-tuned BERT, with an LLM-based explanation step.

## Files

- `app_review_classification.ipynb`

## Tools

scikit-learn, TensorFlow, PyTorch, Hugging Face Transformers, sentence-transformers, FAISS, LangChain, Gradio, NLTK

## Dataset

[Google Play Store Apps (Kaggle)](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

The dataset is not included in this repo.

## Results

From the saved notebook outputs:

Random Forest: accuracy 0.9127, macro F1 0.891 | Linear SVM: 0.9001 / 0.870 | BERT: accuracy 0.9496, macro F1 0.938.

## How to run

1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the dataset from the link above (some notebooks fetch it with `kagglehub`, which asks for Kaggle credentials) and update the data path if needed.
4. Run all cells.

## Author

Mark Ayman
