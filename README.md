# CMP_SCI-4200-Python-for-DS-Project-6-Automated-Extraction-and-Preprocessing-of-YouTube-Comments

Project 6- 70 points
Instructions to upload on Canvas:
1. Submit your .ipynb file, code with outputs in a html file (Go to File->save and export Notebook
as→click HTML.)
Domain: News
Task Details
Automated Extraction and Preprocessing of Public YouTube
Comments from Fox News account.
How can we automatically collect, preprocess, and store public user comments from Fox
News’s official Youtube account (@FoxNews). Click any recent (this week’s shorts/video
which has lots of comments), use API and prepare them in a structured JSON format suitable
for NLP based text analysis such as sentiment analysis.
1. Data Acquisition:
a. Use the Youtube API (We already did this in class) to programmatically extract recent
public comments from posts on the @FoxNews Youtube page. Please mention the
video/reel link in your file.
b. Retrieve fields such as username, comment text, timestamp, and like_count.
2. Data Structuring:
a. Store all retrieved comments in a JSON file for reproducible and machine readable
storage.
3. Data Cleaning & Processing:
a. Preprocess the text by removing emojis, URLs, mentions, hashtags, punctuation, and
stop words.
b. Normalize case and tokenize text using NLTK or spaCy.
4. NLP Analysis:
a. Perform sentiment analysis on the cleaned text for positive/negative comments to
understand public perception.
b. Generate a word cloud or frequency visualization to summarize comment content
trends.
Grading Scale:
1. Data Acquisition (API Implementation) : 15 points
2. JSON Data Structuring: 10 points
3. Text Preprocessing & Cleaning: 15 points
4. NLP Analysis: 10 points
5. Visualization: 5 points
6. Sentiment analysis with Polarity: 15 points
