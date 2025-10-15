# Public Sentiment Trend and WordCloud Analysis on Pertamina Before and After the Viral Pertamax Adulteration Issue Using CNN–LSTM

This project analyzes public sentiment toward Pertamina on social media platform X (formerly Twitter) before and after the viral Pertamax fuel adulteration issue in February 2025. By combining sentiment analysis techniques with deep learning models, the study uncovers how public trust shifted during the crisis.

## 📊 Project Overview

Pertamina plays a critical role in Indonesia’s national energy security, making public perception essential. The Pertamax adulteration issue sparked widespread public reaction online.
This project measures sentiment trends, identifies dominant narratives, and evaluates CNN, LSTM, and CNN–LSTM models for sentiment classification.

**Key findings:**

* Negative sentiment rose from **23.5%** to **48.2%**.
* Positive sentiment fell from **44.6%** to **26.2%**.
* CNN achieved the best classification performance compared to LSTM and CNN–LSTM.
* WordCloud analysis highlighted post-issue keywords such as *“price”*, *“corruption”*, and *“people”*.

## 🧰 Technologies Used

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, TensorFlow/Keras, Scikit-learn, Sastrawi
* **Deep Learning Models:** CNN, LSTM, CNN–LSTM
* **NLP Techniques:**

  * Text preprocessing (tokenization, stopword removal, stemming)
  * InSet Lexicon for sentiment scoring
  * WordCloud visualization
  * TF-IDF and Word Embeddings

## 🧠 Methodology

1. **Data Collection:**
   Web scraping of tweets containing the keyword “Pertamina” from two periods: before and after the viral issue.

2. **Text Preprocessing:**
   Cleaning, normalization, tokenization, stopword removal, stemming.

3. **Sentiment Classification:**
   Using InSet Lexicon to label tweets as Positive, Negative, or Neutral.

4. **Visualization:**
   Exploratory data analysis with bar charts, pie charts, word frequency plots, and WordClouds.

5. **Model Training:**
   Comparison of CNN, LSTM, and CNN–LSTM architectures using accuracy, precision, recall, and F1-score.

## 📈 Results

* CNN performed best overall, although overfitting was observed.
* LSTM and CNN–LSTM struggled to generalize well on short text data.
* Public discourse shifted from institutional themes to criticism about price and trust issues.

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/pertamina-sentiment-analysis.git
   cd pertamina-sentiment-analysis
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:

   ```bash
   jupyter notebook Sentiment_Analysis_Porto.ipynb
   ```

4. Follow the notebook cells step by step to preprocess data, train models, and visualize results.

## 🧭 Future Improvements

* Use transformer-based architectures such as BERT or IndoBERT for better context understanding.
* Balance class distribution to improve model generalization.
* Expand dataset to multiple platforms for richer analysis.
