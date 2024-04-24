# Discord Bot: PythonBot

## Description

PythonBot is a simple Discord bot written in Python using the Discord.py library. It provides several functionalities including responding to specific commands, sending encouraging messages based on certain keywords, fetching random quotes, and rolling a six-sided dice.

## Features

- **Command Handling**: PythonBot responds to specific commands prefixed with `$`.
- **Encouragement Messages**: When users send messages containing certain sad words, PythonBot sends encouraging messages in response.
- **Random Quote**: PythonBot can fetch a random quote from the ZenQuotes API using the `$getQuote` command.
- **Dice Rolling**: With the `$rolldice` command, PythonBot rolls a six-sided dice and displays the result.

## Prerequisites

Before running the bot, make sure you have the following installed:

- Python 3.x
- Discord.py library (`discord`)
- `requests` library
- `dotenv` library

## Setup

1. Clone the repository:

    ```
    git clone https://github.com/Nearezz/PythonBot.git
    ```

2. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the project directory and add your Discord bot token:

    ```
    TOKEN=your_discord_bot_token_here
    ```

4. Run the bot:

    ```
    python bot.py
    ```

## Usage

Once the bot is running and added to your Discord server, you can interact with it using the following commands:

- `$getQuote`: Fetch a random quote.
- `$rolldice`: Roll a six-sided dice.
- Simply typing sad words like "depressed", "unhappy", or "miserable" triggers the bot to send an encouraging message.

## Contributing

Contributions are welcome! If you'd like to add new features, fix bugs, or improve the bot in any way, feel free to submit a pull request.

## Acknowledgments
- PythonBot utilizes the Discord.py library for Discord bot development.
- Quotes are fetched from the ZenQuotes API.
