# Amazon-Reviews-Sentiment-Analysis

This project performs sentiment analysis on Amazon reviews to classify and analyze the sentiment expressed in customer feedback. It leverages natural language processing (NLP) techniques and the VADER SentimentIntensityAnalyzer to determine whether reviews have a positive, neutral, or negative sentiment.

The analysis provides insights into customer opinions and helps understand the distribution of sentiments across the dataset.

**Features:**
Text Preprocessing: Tokenization, part-of-speech tagging, and entity recognition using nltk.
Sentiment Analysis: Sentiment scoring for reviews using VADER SentimentIntensityAnalyzer.
Visualization: Data visualization of sentiment scores and review ratings.
Progress Tracking: Real-time progress displayed during sentiment analysis with tqdm.

____________________________________________________________________________________________________________________________________________________________________

**Dataset:**
The project uses a dataset of Amazon reviews, which includes the following fields:
Id: Unique identifier for the review.
Score: Star rating of the review.
Text: The review text provided by the customer.
Tools and Libraries
Python: The primary programming language used.
Pandas: For data manipulation and analysis.
Matplotlib: For visualizing data.
NLTK: For natural language processing tasks (e.g., tokenization, tagging, entity recognition).
VADER: For sentiment intensity analysis.
TQDM: To display progress bars for iterative processes.

____________________________________________________________________________________________________________________________________________________________________

**Workflow:**
Data Loading: Load the Amazon reviews dataset into a Pandas DataFrame.
Exploratory Data Analysis:
Visualize the distribution of review ratings.
Sentiment Analysis:
Apply VADER SentimentIntensityAnalyzer to score reviews.
Analyze results by merging sentiment scores with the original dataset.
Visualization:
Plot the distribution of sentiment scores.
Correlate sentiment scores with review ratings.
