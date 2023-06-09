# RickGPT Discord Bot

RickGPT is a discord bot that mimics the personality of Rick Sanchez (from the popular show Rick and Morty) in your discord server, using OpenAI's GPT-3 model to generate his witty and unique responses.

## Features

1. `/rickquote`: Generates a random Rick Sanchez quote.
2. `/whatwouldricksay`: Responds to the last message in the channel as Rick Sanchez.
3. `/rick`: Asks Rick Sanchez for his opinion on a specific topic.
4. `/drunkrick`: Asks a drunk Rick Sanchez for his opinion on a specific topic.

## Setup

### Setting Up Your Discord Bot

1. Follow the instructions [here](https://discord.com/developers/docs/getting-started) to create a new bot on the Discord developer portal.
2. Once your bot is created, copy the bot token. This will be used to run your bot.

### Getting Your OpenAI API Key

1. Sign up for an API key at [OpenAI](https://openai.com/blog/openai-api).
2. Once you're approved, you'll be able to find your API key in the OpenAI dashboard.

### Deploying to DigitalOcean

1. Create a new droplet (if you haven't done so already) and SSH into it.
2. Clone your GitHub repository into the droplet.
3. Install Python, pip, and any necessary dependencies (you can use the `requirements.txt` file for this).
4. Set your environment variables (`TOKEN` and `APIKEY`) using the bot token and the OpenAI API key.
5. Run your bot using the command `python3 bot.py` (replace `bot.py` with the name of your python file).

### Making Your Bot Persistent

1. Install `tmux` using the command `sudo apt-get install tmux`.
2. Start a new `tmux` session using the command `tmux new -s bot`.
3. Run your bot inside the `tmux` session.
4. Detach from the `tmux` session using the shortcut `Ctrl+b` followed by `d`. Your bot will continue to run even after you disconnect from the server.

## License

RickGPT is licensed under the MIT License. See `LICENSE` for more information.
