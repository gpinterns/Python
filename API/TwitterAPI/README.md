# Twitter API Explanation

To download all tweets from a specific person via python you have to do the following (look at the [code](https://github.com/gpreports/Python/blob/master/API/TwitterAPI/TwitterAPI.py) for reference):

- Download library Tweepy and used it's [library](http://docs.tweepy.org/en/latest/auth_tutorial.html) for the authentication
- Get the consumer key/secret and access token/tokensecret with the instructions in this [link](https://developer.twitter.com/en/docs/basics/authentication/guides/access-tokens.html)
- On the screen_name you have to write the username of the person you want to download the tweets from with the @, for example "@realdonaldtrump"
- In the variable date1 you choose since when you want to download the tweets, instructions of how it works are on this [link](https://stackoverflow.com/questions/47273935/extract-date-and-time-of-a-tweet-tweepy-python?rq=1) (You can't download more than 3,200 tweets)
