# twitter-bot
Twitter-Bot is a python program which uses tweepy and OpenAi to generate tweets by it's own and then post them on twitter.
Read this article for more information: https://developerwings.com/ai-powered-twitter-bot-using-tweepy-2022/

## Dependencies
Install the following packages using pip.<code>  pip install tweepy </code> &nbsp; <code> pip install openai </code>

## Configuration
Download the file named twitter-bot.py from the repo. <br>
Then create your twitter developer account, and ask twitter for <stronge>Elevated access</stronge> by filling up the application they will provide, wait for like 48 hours for the application to get approved (mine took few minutes) and then create your app on twitter.
<br>
<br>
After you create your app, you should see teh api keys and secret key. Copy them and replace them on line 5 of twitter-bot.py:
<code>
  api_key  ="YOUR API KEY FROM TWITTER"
</code>
and do the same for line 6 and replace it with the api key secret and then get generate access token and secret on twitter developer platform.

Now that we have the twitter ready, let's do the OpenAi, go to openai official website and generate an api key for yourself and then replace it on the line 12:
<code>
    openai.api_key = "OPEN AI KEY"
</code>

And then you are ready to go!
