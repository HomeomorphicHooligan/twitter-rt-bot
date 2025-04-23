# Twitter retweet simple bot
> This is a simple bot created using the Tweepy Python3 library for scraping the Twitter
> API and retweeting the tweets with a specific hashtag, for example #usa2020.
> 
> Created by Pablo Corbalan

So, yeah :), that's it! I have created a small bot for retweeting all the tweets that contain a certain hashtag, and as
everyone should have done, I have made it open source!.

In this repository I'm storing the code (or the script) that actually runs the bot. The code is 100% automatized, and you
will not have to touch it for nothing.

All the configuration of the bot has been externalized to the `configuration.json` file, so you will have to change the 
json file. Inside the json file you can modify lot's of parameters, for example the hashtag the bot should scrape 
from or the language or the tweets, you will also have to **type your credentials**. You can read about how to get your 
Twitter's developer account [here](https://developer.twitter.com/en). Then you will have to create the application and
get the keys and the tokens. Remember **not to publish these keys**, and you should not share them to anybody neither.

### Running the bot
For running the bot, we are going to use git and python:
```shell
# clone the repository using Git
git clone https://github.com/twitter-rt-bot.git
# move inside the repository
cd twitter-rt-bot/
# edit the configuration file with your credentials and stuff.A
```
Now, run the `main.py` file using the Python3 interpreter:
```shell
python3 main.py
```
### License and terms
This program is under the MIT license, read it [here](LICENSE).
