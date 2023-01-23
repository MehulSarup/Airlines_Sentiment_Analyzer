# Airlines_Sentiment_Analyzer
# Introduction
British Airways (BA) is the flag carrier airline of the United Kingdom (UK). Every day, thousands of BA flights arrive to and depart from the UK, carrying customers across the world. Whether it’s for holidays, work or any other reason, the end-to-end process of scheduling, planning, boarding, fuelling, transporting, landing, and continuously running flights on time, efficiently and with top-class customer service is a huge task with many highly important responsibilities.

Customers who book a flight with BA will experience many interaction points with the BA brand. Understanding a customer's feelings, needs, and feedback is crucial for any business, including BA. So I have scraped the reviews data from the web and then done a Sentiment Analysis on the reviews of British Airways to find what gives the passengers a good or bad experience.

# Aim
To scrape the reviews from website and then analyze the sentiments of the passenger's reviews on British Airways airlines

# Techniques
I have used BeautifulSoup to scrape the data from the web. Then used the NLP libarary nlptk to perfrom text pre-processing to remove special characters, numbers, stopwords and then lemmatize the text to get the root word according to the context. Then I used nlptk's VADER lexicon model to perform sentiment analysis which provided me sentiments the reviews fall in - "Positive, "Negative", "Neutral". For positive and negative reviews, I created wordclouds to visualize the words that had more empahsis on in the reviews.

# Conclusion
After classifying the sentiment of the data using the NLTK VADER model, the text was visualized for insights through word clouds. From that it was deduced that 50.4% were positive reviews in which customers had mentioned easy, polite and helpful for the staff and crew of British Airways. They have described the airlines using words like Great and Incredible. In the 39.4% of Negative reviews, customers have complained on the economy, premium and business classes, and the airlines website. They have mentioned words like bad, old and unlucky which shows that there are few services which could be improved to ensure customer satisfaction.

To be able to identify if a review is positive or negative, a Logistic Regression model was developed having an accuracy of ~85%. With further improvements to the model like tuning the hyper parameters and having more data, would definitely boost the accuracy of the model
