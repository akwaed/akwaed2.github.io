# ChatGPT Twitter Bot

This is a simple Twitter bot that uses OpenAI's GPT-3.5 model to generate responses to tweets that mention it. The bot searches for mentions of its own Twitter handle and responds with a message generated by the GPT-3.5 model.

## Requirements
- Python 3
- Tweepy
- OpenAI API key


### Features
- Searches for mentions of its own Twitter handle.(@uky_cs498)
- Generates a response to the mention using GPT-3.5.
- Replies to the mention with the generated response.

## Scope (User Stories)
As a user, I want to be able to mention the bot on Twitter and receive a response.
As a developer, I want to be able to easily modify the code.

## Notes
- This code is written in Python and requires Tweepy and an OpenAI API key to run.
- The bot will continuously run and search for mentions of its own Twitter handle. To stop -the bot, you must manually terminate the process.
- The GPT-3.5 model used by this bot requires an active OpenAI API key, which must be set   up prior to running the bot.
