## Executive Summary
In our industry corporations are always looking for ways of trimming the costs of doing business. Data providers such as Google, Amazon,  Facebook, and Reddit have web services arms. These web services sell the information of their users to other companies as an additional source of revenue. Selling their clients metadata is an opportunity for the data providers (Reddit, Facebook, AWS, etc.) to upsell their other products (software, consulting) with the data provided. We believe that instead of paying exorbitant amounts of money to these big corporations, we can find cost-benefit solutions in-house.

As a member of the Business Analytics team at the latest app launched in the online dating sphere. We believe that we can provide the same services that Amazon and Reddit provide internally saving our company money. Currently, we are paying for Reddit's web services for the keyword data on a multitude of Reddit's dating subreddits. We in our analysis have found that we might be able to mine this data from Reddit directly and find keywords at a fraction of the cost.

Our Analytics team created in-house classification models, to find the keywords that classify different dating demographics.  If we can successfully classify Reddit posts with a high degree of accuracy we can avoid the high fees of Reddit's Webservices. We know that Reddit's API is a cost-effective way of gathering data, so we found two subreddits that represent two of our largest demographics. "r/datingover30", and "r/datingover40" two subreddit communities that reflect the thirty to forty-year-old demographic that we want to be able to classify. Our analytics team used Reddit's API to mine the data of 12000 Reddit posts, 6000 from each subreddit and ran four unique Natural Language Processing (NLP) models. We found the Support Vector Machine (SVM) classified the Reddit post with a 73% accuracy. 73% accuracy is a 31% improvement over our worst-case scenario of 50%. However, this is not accurate enough to consistently find keywords particular to each demographic.

In conclusion, we found the two subreddits, "r/datingover30" and "r/datingover40" are so similar that our machine learning algorithms found it difficult to classify one from another.  In future work, we should look into a better way to classify the lexicon of the two groups. What do 40-year-olds say that 30-year-olds don't? Perhaps the answer lies with emojis or sentiment analysis.
