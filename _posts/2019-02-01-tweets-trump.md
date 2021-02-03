---
layout: post
title: "Tweets Trump"
date: 2019-02-01
related_image: /images/trump_twitter.jpg
---
## What kind of language and tone does Donald Trump use in his tweets and how does this relate with the world close around him?

For this project, I analysed the tweets from the first 2 weeks of January 2019. If you download Twitter data from Twitter, a lot of data is available per tweet: 
- Location from where the tweet has been sent
- Device from which the tweet has been sent
- The tweet itself
- The number of likes/retweets
- The number of followers
- etc.<br/>

Below you can see a word cloud of Trump's most used words (left) and word combinations (right). Can you recognize someone and/or something in these pictures?<br/>
![Word cloud Trump](/images/trump_wordcloud.png) ![Word cloud Whitehouse](/images/wh_wordcloud.png)

In both graphs below, you can see the top 10 words that the president uses. The color indicates whether the word is positive, neutral or negative (this was determined by the computer using sentiment analysis). The left barplot is for the first 2 weeks of 2019 and the right one for the last 4 years (2014-2018). It is remarkable that the president mostly uses neutral words. Also, he talks about himself less lately and more about border security. That is reasonable because of the shutdown in the US (at the time of writing).<br/>
![Popular words last 2 weeks of 2019](/images/popularwords.png) ![Popular words 2014-2018](/images/popularwords2.png)

Every tweet got a grade for its positivity ranging from -1 (very negative) to 1 (very positive). If you add all the grades up, you get a cumulative plot (see below). The first one is for the first 2 weeks of 2019 and the second one for the year 2017. You can see that both graphs are increasing. Therefore, one could say that, on average, the president tweets positively. However, there are some drops, which are marked by blue and red arrows. These drops are when the president gets really angry. Every arrow has a text box attached to it with the reason of such drops.<br/>
![CDF sentiment analysis last 2 weeks](/images/cdf1.png) ![CDF sentiment 2017](/images/cdf2.png)

Up till now, we have looked into the first part of the main question: *what language and tone does the president use in his tweets?* Now it is time to look at the second part of the main question: how does this relate with the world close around Donald Trump? 2 factors that are close around Donald Trump are his location and the phone he uses to tweet from. The secret service has automatically set his location at Washington DC (so nobody can follow the president), so I could not look further into that. However, I could see what device/app the president uses to tweet. Below you can see the division of his phone-use from 2014 to 2018. Also, you can see that his staff (who uses Twitter Web Client) tweets the most positively.<br/>
![Tweet devices](/images/tweetdevices.png) ![Tweet sources](/images/tweetsources.png)

Another factor that is close around Donald Trump, is, just like anybody else: time. I wondered whether the president might be a morning person or evening person. In the graph below, you can see that his sentiment decreases during the day. So, if you want something from the president, you better ask it in the morning!
Fun fact: the president does not tweet between 05:00 and 10:00!<br/>
![Tweet sentiment](/images/tweetsentiment.png) 

Donald Trump is also close related with what the people from the USA are thinking and searching for on Google. If you plot the number of tweets containing a popular term (in this case "border") and its popularity on Google in the USA, you can see that there seems to be a correlation in the second week of January 2019. So, there is kind of a relation between both.<br/>
![Google trends](/images/googletrends.png) 

Trump is also close with the stock market. I wondered if there would be a relation between the number of times that he mentions the trade war with China and the stock price of, for example, the Dow Jones Index (left) or the Chinese Yen.
As you can see, both graphs do not show a clear correlation.<br/>
![Relation with DJI](/images/dji.png) ![Relation with Chinese Yuan](/images/yuan.png)

Just like anyone else, the weather influences the president. Big rainstorms seem to stimulate his sentiment, therefore I called that "cozy rain". Smaller rainstorms result into a considerable drop in his sentiment. So, there is clearly a relation between the weather and the president's sentiment.<br/>
![Relation with weather](/images/weathertrump.png)]

If you click [here](https://trumpgolfcount.com/displayoutings), you will be directed to a website which records when and where the president plays golf. I used these data to compare the president's sentiment when he is playing with his sentiment when he does not play golf. As you can see in the boxplot below, there does not seem to be a relation between the president's golf activities and his sentiment.<br/>
![Relation with golfing](/images/golfingboxplot.png)]

As you can see below, the president's sentiment has been approximately the same over the years. However, the spread in 2018 is slightly bigger than in the previous years.
![Sentiment over the years](/images/sentimentboxplot.png)]

## Conclusion
In the last 2 weeks the president used border & border security the most. In the last 4 years he used trump, great  and president the most. Also, he mostly uses neutral words and sometimes a positive word. There were several factors that I wanted to compare with the president's sentiment. Below you can see which of them has a relation with sentiment and which do not.<br/>
Relation with sentiment: 
- Time
- Source/device
- Google Trends
- Weather<br/>

No relation with sentiment:
- Location
- Stock Prices
- Playing Golf





