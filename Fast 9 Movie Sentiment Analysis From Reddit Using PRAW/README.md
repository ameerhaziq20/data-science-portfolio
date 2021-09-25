![jpg](https://image11.m1905.cn/uploadfile/2021/0421/20210421100242955450.jpg)

Let's analyze the reviews for the Fast & Furious 9 movie. If you’re unfamiliar with the premise of the latest outing for Dominic Toretto (played by Vin Diesel) and his family, here’s a brief recap. Following the events of The Fate of the Furious, the crew must face off against Jakob (played by John Cena), who is Dominic’s younger brother and a deadly assassin. Here, we will scrape comments from a Reddit post discusing about their thoughts about the movie.

# 1. Questions

This analysis will try to answer the following questions:
* What are the Redditors comments on the Fast 9 movie?
* Are the comments mostly potray their opinions or stating a fact?
* What are the positive and negative comments mostly about?

# 2. Measurement Priorities

* The polarity of the Redditor's comments by analyzing the sentiment's polarity score. 
* The subjectivity of the Redditor's comments by analyzing the subjectivity score of the sentiments.
* Creating a collection of words for each polarity of sentiments using word clouds.

# 3. Data Collection

* Source
    * The comments collected will be from reddit.com using their API.
    * The python library PRAW will be used to gather the comments.

* Storage
    * The collected comments will be stored in a CSV file.
    * The cleaned comments will also be stored as both CSV file.
    
# 4. Report
* Sentiment polarity count

![png](https://raw.githubusercontent.com/ameerhaziq20/ameerhaziq20.github.io/main/_projects/Fast%209%20Reddit%20Comments%20Sentiment%20Analysis%20using%20NLTK%20and%20PRAW/output_72_0.png)
    
**Description:** The bar chart shows that count of polarity labels from the Fast 9 movie Reddit comments. From the chart we can see that most of the comments are 'weak positive'. This shows that Reddit comments on the post are reacting slightly positive towards the movie.

* Distribution of polarity scores

![png](https://raw.githubusercontent.com/ameerhaziq20/ameerhaziq20.github.io/main/_projects/Fast%209%20Reddit%20Comments%20Sentiment%20Analysis%20using%20NLTK%20and%20PRAW/output_67_0.png)
    
**Description:** The polarity score distribution graph shows a unimodal bell shaped distribution. A left skew is shown from the distribution which tells us that the mean gets pulled towards the tail, and is less than the median. 

* Distribution of subjectivity scores

![png](https://raw.githubusercontent.com/ameerhaziq20/ameerhaziq20.github.io/main/_projects/Fast%209%20Reddit%20Comments%20Sentiment%20Analysis%20using%20NLTK%20and%20PRAW/output_69_0.png)
    
**Description:** The subjectivity score distribution graph shows a bimodal distribution. A slight right skew is shown from the distribution which tells us that the mean gets pulled towards the tail, and is greater than the median. 

* 
![png](https://raw.githubusercontent.com/ameerhaziq20/ameerhaziq20.github.io/main/_projects/Fast%209%20Reddit%20Comments%20Sentiment%20Analysis%20using%20NLTK%20and%20PRAW/output_74_0.png)
   

**Description:** The bar chart shows that count of subjectivity labels from the Fast 9 movie Reddit comments. From the chart we can see that most of the comments are 'objective'. This means that most of the collected comments are mostly factual albeit by only a small margin of difference with the count of subjective comments. 
