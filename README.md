 # ChatGPT Discord Bot

This is a simple Discord bot that allows users to interact with the ChatGPT AI model. The bot is built using the Discord.py library and the OpenAI API.

## Installation

To install the bot, you will need to have Python 3.6 or later installed. You can download Python from the [Python website](https://www.python.org/downloads/).

Once you have Python installed, you can install the required dependencies by running the following command in your terminal:

```
pip install -r requirements.txt
```

This will install the Discord.py library, the OpenAI API, and the Python dotenv library.

## Configuration

To configure the bot, you will need to create a `.env` file in the same directory as the `run.py` file. The `.env` file should contain the following two lines:

```
CHATGPT_API_KEY=<your ChatGPT API key>
DISCORD_TOKEN=<your Discord bot token>
```

You can get your ChatGPT API key by creating an account on the [OpenAI website](https://beta.openai.com/). You can get your Discord bot token by creating a bot on the [Discord Developer Portal](https://discord.com/developers/applications).

## Usage

To start the bot, simply run the `run.py` file. The bot will then connect to the Discord server and start listening for messages.

Users can interact with the bot by sending messages that start with `/ai`, `/bot`, or `/chatgpt`. The bot will then respond to the message with a response from the ChatGPT AI model.

## Example

Here is an example of a conversation between a user and the bot:

```
User: /ai What is the capital of France?
Bot: The capital of France is Paris.
User: /bot Who is the president of the United States?
Bot: The president of the United States is Joe Biden.
User: /chatgpt What is the meaning of life?
Bot: The meaning of life is a question that has been pondered by philosophers and theologians for centuries. There is no one answer that is universally agreed upon, but some possible answers include:

* To find happiness and fulfillment.
* To make a difference in the world.
* To learn and grow as a person.
* To connect with others and build relationships.
* To experience the beauty and wonder of the world.

Ultimately,
```
NOTE: As of March 2023, openAi's chatGPT API will require you to own a paid account to have access to use it. Keep this in mind while developing. Happy coding!
