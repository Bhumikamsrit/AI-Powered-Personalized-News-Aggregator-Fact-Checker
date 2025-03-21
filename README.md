# AI-Powered-Personalized-News-Aggregator-Fact-Checker
Project Overview
The Personalized News Aggregator is an AI-driven application designed to curate personalized news feeds. It leverages advanced Natural Language Processing (NLP) techniques to fetch, summarize, and analyze news articles based on user-defined keywords. The application provides a unique experience by tailoring content to user preferences, making it a useful tool for staying informed on topics of interest.

Features
Automated News Fetching: Retrieves the latest news articles from NewsAPI based on specified keywords.
AI-Powered Summarization: Generates concise summaries of articles using a transformer-based model.
Sentiment Analysis: Provides sentiment scores to indicate the emotional tone of the articles.
Personalized Content: Customizes the news feed according to user-defined interests.
Methodology
Data Collection
The application uses the NewsAPI to gather news articles. Users can specify keywords that reflect their areas of interest, and the application retrieves relevant articles.

Text Summarization
A pre-trained transformer model from the transformers library is used to summarize the articles. The model condenses the main points of each article into a brief summary, making it easier for users to grasp the essential information quickly.

Sentiment Analysis
The TextBlob library is employed for sentiment analysis. It assigns a polarity score to each summary, ranging from -1 (negative) to 1 (positive), indicating the overall sentiment of the article.

Personalization
The application personalizes the news feed by filtering and presenting articles based on user-defined keywords. This customization ensures that users receive content that aligns with their interests.

Data Storage
The summarized articles, along with their sentiment scores and other metadata, are stored in a pandas DataFrame. The data can be exported to a CSV file for further analysis or sharing.
