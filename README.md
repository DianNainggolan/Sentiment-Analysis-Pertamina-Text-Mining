# Public Sentiment Trend and WordCloud Analysis on Pertamina Before and After the Viral Pertamax Adulteration Issue Using Deeplearning

This project analyzes public sentiment toward Pertamina on X (formerly Twitter) before and after the viral Pertamax adulteration issue in February 2025. Using InSet Lexicon and deep learning models (CNN, LSTM, and CNN–LSTM), it uncovers how public narratives shifted and how trust was impacted during the crisis.

---

## 📁 Project Files

This repository contains all the data and supporting files needed to reproduce the analysis:

* `pertamina_before.csv` — Tweet dataset collected **before** the Pertamax issue
* `pertamina_after.csv` — Tweet dataset collected **after** the Pertamax issue
* `positive.tsv` — Positive lexicon words for sentiment classification
* `negative.tsv` — Negative lexicon words for sentiment classification
* `Sentiment_Analysis_Porto.ipynb` — Jupyter notebook containing the full analysis pipeline
* `requirements.txt` — Python dependencies for running the project

---

## 🧠 Project Overview

In February 2025, the Pertamax adulteration issue went viral, triggering a massive wave of online discussions.
This project:

* Measures sentiment trends before and after the issue.
* Identifies dominant keywords and narrative shifts.
* Evaluates the performance of multiple deep learning models in sentiment classification.
* Demonstrates how online sentiment can reflect and amplify public trust dynamics.

---

## 🧰 Technologies Used

* **Programming Language:** Python
* **Libraries & Frameworks:**
  Pandas, NumPy, Matplotlib, Seaborn, WordCloud, NLTK, Sastrawi, Scikit-learn, TensorFlow, Keras
* **Tools:** Jupyter Notebook
* **Approach:** NLP (Natural Language Processing) + Deep Learning

---

## 🧪 Methodology

1. **Data Collection:**
   Tweets containing the keyword “Pertamina” were collected in two time periods: before and after the viral Pertamax issue.

2. **Text Preprocessing:**
   Cleaning text, normalizing case and slang, tokenization, stopword removal, stemming using Sastrawi.

3. **Sentiment Labeling:**
   Tweets were labeled Positive, Negative, or Neutral using the InSet Lexicon sentiment scoring.

4. **Exploratory Analysis:**
   Sentiment distribution was visualized with bar charts, pie charts, and word frequency plots.

5. **WordCloud Analysis:**
   Visualized narrative changes and keyword shifts.

6. **Model Training:**
   Deep learning models (CNN, LSTM, CNN–LSTM) were trained on the labeled data to classify sentiment polarity.

7. **Model Evaluation:**
   Models were evaluated based on accuracy, precision, recall, and F1-score.

---

## 🧠 Key Findings

* Negative sentiment toward Pertamina **increased from 23.5% to 48.2%** after the issue.
* Positive sentiment **dropped from 44.6% to 26.2%**, showing a clear decline in public trust.
* **CNN achieved the best accuracy** among the tested models but experienced overfitting.
* WordCloud analysis revealed new dominant terms such as *“price”*, *“corruption”*, and *“people”*.
* Public narratives shifted from neutral or supportive discussions to criticism and distrust.

---

## 📈 Results Summary

| Model    | Accuracy | Notes                                                     |
| -------- | -------- | --------------------------------------------------------- |
| CNN      | Highest  | Strong performance but signs of overfitting               |
| LSTM     | Lower    | Struggled with short text context                         |
| CNN–LSTM | Moderate | Improved feature learning but not optimal on this dataset |

WordCloud visualizations reinforced the sentiment results, highlighting critical narrative shifts post-issue.

---

## 🚀 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/pertamina-sentiment-analysis.git
   cd pertamina-sentiment-analysis
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook**

   ```bash
   jupyter notebook Sentiment_Analysis_Porto.ipynb
   ```

4. **Run the cells** step by step to:

   * Preprocess and label data
   * Visualize sentiment distribution and word frequencies
   * Train and evaluate models
   * Generate WordCloud visualizations

---

## 🧭 Future Work

* Integrate transformer-based models (e.g., BERT / IndoBERT) to better capture linguistic context.
* Balance class distribution to reduce overfitting and improve generalization.
* Expand data sources beyond X (Twitter) for richer, multi-platform analysis.
* Automate real-time sentiment monitoring for crisis communication strategies.

---
