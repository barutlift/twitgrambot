# twitgrambot
this bot shares the last post shared in the telegram group on twitter

First, you will need to create a Telegram bot and obtain its API token.
Next, you will need to create a Twitter developer account and obtain your API keys.
Using the python library python-telegram-bot you can interact with Telegram API and get the latest messages sent to your bot.
Using the python library tweepy you can interact with the twitter API and post tweets.
Then, you can write a script that gets the latest messages sent to your Telegram bot, and then posts them on Twitter using the API keys you obtained.
Finally, you can use a scheduler like cron to run your script at regular intervals to continuously monitor Telegram for new messages and post them to Twitter.
