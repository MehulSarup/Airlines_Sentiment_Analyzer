# Airlines_Sentiment_Analyzer
# Introduction
British Airways (BA) is the flag carrier airline of the United Kingdom (UK). Every day, thousands of BA flights arrive to and depart from the UK, carrying customers across the world. Whether it’s for holidays, work or any other reason, the end-to-end process of scheduling, planning, boarding, fuelling, transporting, landing, and continuously running flights on time, efficiently and with top-class customer service is a huge task with many highly important responsibilities.

Customers who book a flight with BA will experience many interaction points with the BA brand. Understanding a customer's feelings, needs, and feedback is crucial for any business, including BA. So I have scraped the reviews data from the web and then done a Sentiment Analysis on the reviews of British Airways to find what gives the passengers a good or bad experience.

# Aim
To scrape the reviews from website and then analyze the sentiments of the passenger's reviews on British Airways airlines

# Techniques
I have used BeautifulSoup to scrape the data from the web. Then used the NLP libarary nlptk to perfrom text pre-processing to remove special characters, numbers, stopwords and then lemmatize the text to get the root word according to the context. Then I used nlptk's VADER lexicon model to perform sentiment analysis which provided me sentiments the reviews fall in - "Positive, "Negative", "Neutral". For positive and negative reviews, I created wordclouds to visualize the words that had more empahsis on in the reviews.

