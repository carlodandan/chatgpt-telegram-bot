## ChatGPT Telegram Bot

* Create Bot using [@BotFather](https://t.me/BotFather). Name it any name you want.
* Once you've created the bot, it will give you an telegram bot API token. Keep this token safe, as you'll need it later.
* Create an account in https://platform.openai.com/, and got to your Profile and click View API Keys. Generate new key, and save it.

Setup Local Environment:
* Install `python3-pip`:
```
sudo apt-get install python-pip
```
* Install `python-telegram-bot`:
```
pip install python-telegram-bot --upgrade
```
* Install `openai`:
```
pip install openai
```
* Export `OPENAI_API_KEY`:
```
export OPENAI_API_KEY="<openai api key>"
```
* Export `TELEGRAM_BOT_TOKEN`:
```
export TELEGRAM_BOT_TOKEN="<telegram bot token>"
```
* Run:
```python3 gpt_bot.py```

Since this is a local setup, once you close the terminal, the bot will not be able to answer your question anymore. You can publish it in a server/cloud, so you can run it virtually. At this point, it's now up to you. Also, for Free users, there's a limit on how much request you can make or token you can spend.

## Resources
* OpenAI (ChatGPT) - https://platform.openai.com
* Python-Telegram-Bot - https://github.com/python-telegram-bot
* Telegram - https://core.telegram.org/
