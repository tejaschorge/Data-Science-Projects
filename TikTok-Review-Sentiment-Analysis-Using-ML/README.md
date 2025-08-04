# 🎵 TikTok Review Sentiment Analysis

This project presents a comprehensive end-to-end sentiment analysis pipeline designed to extract insights from user-generated TikTok content using Python, Natural Language Processing (NLP), and Machine Learning. The system processes thousands of user comments to determine their underlying sentiment—Positive, Negative, or Neutral, using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool from the NLTK library. Extensive text preprocessing is applied, including lowercasing, punctuation removal, stopword filtering, and stemming, to ensure clean input for sentiment classification.

The cleaned and analyzed data is visualized using advanced plotting libraries like Matplotlib and Plotly, offering intuitive representations such as sentiment-specific word clouds and interactive pie charts. The project also includes logic to assess the overall mood of the dataset based on cumulative sentiment scores. This solution helps in understanding public opinion on TikTok content, making it valuable for creators, influencers, and marketers aiming to measure engagement and audience perception at scale.

**Key features include:**

  - Text preprocessing using regular expressions, NLTK stopwords, and stemming.

  - Sentiment classification using VADER's compound scoring system.

  - Visual insights via word clouds and sentiment distribution pie charts.

  - Aggregated sentiment interpretation to determine overall audience tone.

  - Applicable to any short-form content platform, especially TikTok.

This project demonstrates core NLP techniques, sentiment analysis workflows, and effective data visualization strategies, making it a strong foundation for social media analytics and opinion mining tools.

---

## 🔄 Project Workflow

1. Data Collection

    - Load a dataset containing TikTok user comments or reviews in CSV format.

    - Extract relevant columns (e.g., content, score) for analysis.

2. Text Preprocessing

    - Convert text to lowercase.

    - Remove noise such as URLs, HTML tags, punctuation, digits, and newline characters using regular expressions.

    - Remove English stopwords using NLTK.

    - Apply stemming to reduce words to their base form using NLTK's SnowballStemmer.

3. Exploratory Data Analysis (EDA)

    - Use value_counts() to analyze score distribution.

    - Create pie charts using Plotly to visualize sentiment proportions.

    - Generate word clouds to highlight frequently used words in positive, negative, and neutral comments.

4. Sentiment Analysis

    - Use NLTK’s SentimentIntensityAnalyzer (VADER) to compute sentiment scores (Positive, Negative, Neutral) for each comment.

    - Append these scores to the dataset for further analysis.

5. Visualization

    - Generate sentiment-specific word clouds (e.g., for Positive vs. Negative reviews).

    - Plot interactive sentiment distribution using Plotly pie charts.

    - Display overall sentiment of the dataset based on total score aggregation.

6. Sentiment Interpretation

    - Sum all sentiment scores to determine whether the general tone of TikTok comments is Positive, Negative, or Neutral.

    - Print or visualize the final sentiment result with emoji indicators for quick understanding.

7. Final Output

    - A cleaned, structured dataset with sentiment scores.

    - Visual insights that can be used for influencer marketing, brand reputation monitoring, or audience engagement analysis.
  
---

## 📊 Results

The sentiment analysis model successfully processed and evaluated thousands of TikTok user comments with high efficiency and accuracy. After cleaning and analyzing the dataset, the model assigned individual sentiment scores (positive, negative, neutral) to each comment using VADER, a rule-based sentiment analysis engine fine-tuned for social media text.

These results demonstrate the effectiveness of combining lightweight NLP techniques with real-world user data for deriving actionable insights. The sentiment classification and visualization pipeline provides an intuitive understanding of audience mood—making it valuable for content strategists, brand marketers, and platform researchers.


