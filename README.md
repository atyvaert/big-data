# Big_Data

•	The volume of a brand’s tweets 
•	The language used in the tweets (words, sensitivity, emojis, ...)               => Artur Tyvaert
•	The timing of tweets posted by a brand

•	The number of followers of the brand 
•	The number of likes for a brand post                                            => Konstantin Lazarov
•	The number and impact of influencers for each brand 

•	The volume of tweets 
•	The timing of tweets                                                            => Viktor Vandenbulcke
•	The number of followers of users 

•	The number of likes for a tweet
•	The level of engagement for each tweet                                          => Lennert Van Den Broeck
•	The level of social media activity for user 

•	The evolution of tweet activity 
•	The evolution of tweet engagement 
•	The level of social media activity vs level of engagement                       => Wouter Dewitte 
•	The volume of influencer activity vs level of engagement 
...


Sources:

https://developer.twitter.com/en/docs/twitter-api/data-dictionary/introduction
https://github.com/caocscar/twitter-decahose-pyspark

Dependant variable ideas:

- [Google Trends](https://trends.google.com/trends/?geo=BE)

With this tool, you can look up keywords, search terms. Your receive insights in the popularity of the search term.
First, you see the popularity throughout time.
Next, you see the popularity per region. This can be interesting if we want to conduct a Market Expansion Research.
Finally, related subjects and related search terms are also given.

The interesting part is that all this data can be downloaded and used.

The popularity of search term on day x can be linked to tweet intensity/engagement on day x - 1.

We can do this for multiple locations (location of term popularity in Google Trends combined with location of tweet posting) and look in which region the tweet intensity/engagement has the most impact on popularity of the keyword.
