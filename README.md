# Rick Discord Bot

A Discord bot that generates random Rick quotes and responds to the last message in the channel as Rick Sanchez, using the OpenAI API.

## Features

- Generates a random Rick quote.
- Responds to the last message in the channel as Rick Sanchez, using OpenAI's GPT-3.

## Installation

1. Clone this repository: `git clone https://github.com/yourusername/rick-discord-bot.git`
2. Install the dependencies: `pip install -r requirements.txt`
3. Set your Discord bot token and OpenAI API key as environment variables:
    - For Unix-based systems: `export DISCORD_TOKEN="your-token-here"` and `export OPENAI_KEY="your-api-key-here"`
    - For Windows: `set DISCORD_TOKEN=your-token-here` and `set OPENAI_KEY=your-api-key-here`
4. Run the bot: `python3 bot.py` (replace `bot.py` with the name of your Python script)

## Usage

- Use `/rick` to generate a random Rick quote.
- Use `/rickrespond` to have the bot respond to the last message in the channel as Rick Sanchez.

## License

This project is licensed under the terms of the MIT License.