
Opinion Minging and Sentiment Analysis 
==================

The goal of this project was to find out about early market reaction to iphone X which has been announced on Spetember 12, 2017. This was achieved by mining and analyzing people opinions on a relevent website (https://techcrunch.com/2017/09/13/i-dont-want-the-new-iphone-x-and-i-cant-be-alone/).

## Input
 
Users' online reviews and comments from www.techcrunch.com for iPhone X which will be released in November 2017.

## Output

People opinions sentiments for new iPhone X

## Dependencies

For running this code you need to have Python 3.6 and install sklearn, lxml, requests, and pandas packages on your machine. 

## The code consists of two steps

A- Crawling online comments from web, cleaning up data and extracting important information from html content:

I developed a Python web crawler to pull out people's comments from techcrunch.com websites where they discussed the new iPhone. This crawler downloads all reviews and comments posted by people. I used lxml and requests Python libraries to extract important data from HTML contents.

B- Running sentiment analysis using my developed sentiment analysis model:

For the second step, I used Amazon user reviewes for a verity of unlocked mobile phones. Using ratings and text of reviews, I developed a logistic regression model to distinguish postitive and negative reviews. I used "CountVectorizer" from sklearn.feature_extraction.text
library to find probabilty of 1-word and 2-words combinations in postitive and negative reviews.
After verifying accuracy model which is around 96% and finding 10 most commen words in postive and negative reviews, I applied the developed model ot the extract comment list. 

## Results

I collected 128 comments( including replies to comments) in total where 78 positive, and 50 of them were labelled 
negative respect to the topic (iPhone X). Below is the details:

	pos=60.9%
	neg=39.1%


## Observations

Above results show how people thought about the iPhone X release after its demo on September 12, 2017 and it does not reflect 
the developer's opinion.
 
If you have any question regard to this project, please contact me @ "ehsan DOT sadeghi AT gmail DOT com".
