
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

We developed a Python web crawler to pull out people's comments from techcrunch.com and cnet.com websites where they discussed th new released iPhone. This crawler downloads all reviews posted by people. Next, we used BeautifulSoup Python library to extract important data from HTML contents: www.crummy.com/software/BeautifulSoup/.

B- Running sentiment analysis using PycURL and text-processing API:

For the second step, we used a machine learning algortihm for sentiment analysis to find out what people think about the iPhone 5. We found an available API for the sentiment analysis implemented by Python NLTK (text-processing.com/demo/sentiment/). Thus, we used this website API in order to analyze the polarities of posted comments. For sending HTTP requests to text-processing website, we used a Python library called PycURL. PycURL is a Python interface to libcurl (www.pycurl.sourceforge.net/).

## Results

For techcrunch.com, we collected 79 comments in total where 10 of them were labeled neutral, 13 positive, and 56 of them were labelled 
negative respect to the topic (iPhone 5). Below is the details:

	pos=16.4%
	neg=71%


## Observations

Above results show how people thought about the iPhone X release after its demo on September 12, 2017 and it does not reflect 
the developer's opinion.
 
If you have any question regard to this project, please contact me @ "ehsan DOT sadeghi AT gmail DOT com".
