# TwitterBot

This is a console application twitter competition bot, it will search for keywords, filter tweets and then retweet.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Installing

Clone or download this repository
```
Button is at the top of the repository page
```

Change information the config.json file to your own (should look something like below)

```
{
  "SearchKeywords": [
    "rt to win",
    "retweet and win",
    "giveaway"
  ],
  "IgnoreKeywords": [],
  "ConsumerKey": "Your Consumer Key",
  "ConsumerSecret": "Your Consumer Secret",
  "AccessToken": "Your Access Token",
  "AccessSecret": "Your Access Secret",
  "LastTweetId": 0,
  "TweetDelay": 60000
}
```

Run "TwitterBot.exe", simple as that!
```
"Config.json" must be in the same directory as "TwitterBot.exe"
```
