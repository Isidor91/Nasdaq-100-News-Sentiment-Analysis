This script provides a foundation for analyzing and visualizing sentiment in news articles about the NASDAQ-100. Feel free to expand and customize it according to your needs.

Explanation

1. Fetch News: fetch_news retrieves news articles about the NASDAQ-100 using NewsAPI. Replace your_news_api_key_here with your actual API key.

2. Analyze Sentiment: analyze_sentiment uses TextBlob to compute the sentiment polarity of the article descriptions.

3. Visualize Sentiment: plot_sentiment uses matplotlib and seaborn to create a histogram of sentiment scores, including a kernel density estimate (KDE) for smoothness.

4. Main Function: The main function integrates the fetching, analyzing, and plotting of news. It prints out the title, description, and sentiment score for each article and then plots the distribution of sentiment scores.
