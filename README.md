# TerBot

TerBot is a **Shitty** botting tool for [territorial.io](https://territorial.io) which puts a bunch of bots in your game. It's not very efficient because it uses Selenium, which takes up a lot of resources. But it kinda gets the job done. At 25 stars, I might try to recode it to communicate with the game's WebSocket server instead of using Selenium windows for each client, which will make it a lot more efficient and allow people to run basically an infinite number of bots.

## Features

- Automated game joining
- Multiple bot instances
- Optional proxy support
- Customizable clan tags

## Quick Start

If you don't want to mess with Python, you can use the executable

1. Download `main.exe` from [Here](https://github.com/KingBob838/TerBot/releases/download/Windows/main.exe)
2. Run it like any other program

## Setup for Python SRC

If you prefer running the Python script:

1. Make sure you have Python 3.x installed.
2. Clone the repo or download the source files.
3. Run `setup.bat` to install dependencies and start the bot.

Or do it manually:

```sh
pip install -r requirements.txt
python main.py
```

## Usage

1. Choose a clan tag (optional)
2. Specify the number of bots to run
3. Decide if you want to use proxies
4. Select which game to join

## Requirements

- Python 3.x (if not using the executable)
- Chrome browser

## Join the Discord

Join the Discord for support, updates, and chatting:

[Join TerBot Discord](https://discord.gg/cQuMEBNB)

## Website

Check out [TerBot.bar](https://terbot.bar)
