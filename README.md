# 

A simple game of snakes and ladders created on `Python 3.11` as a school project.

# Installation

### Dependencies

- `Python 3.11`
- `termcolor 1.1.0`

### Setup

1. Install `Python 3.7.6`

2. Install and activate the virtual environment
```
pip install virtualenv
```

If you haven't already, clone this project from your fork, and enter the main directory.

```
# on linux/macOS
source env/bin/activate
# on windows
env\bin\activate
```

3. Install all dependencies

```
pip install -r requirements.txt
```

3. Run it

```
python snakes.py
```

# Rules

1. After running the game, the you'll be asked about the number of users ranging from 1 and 4 

2. The grid gets loaded with user's beed at the start position

3. Press <kbd>roll</kbd> to roll the dice.

4. With each roll the grid gets updated with an updated score the goal.

5. The first person to reach the end will be declared as a winner

# technical task:

Create a game in which players can control cats, but not with regular buttons, but remotely - via a Telegram bot.

The game server videos will have a flask application with a database.

The Telegram bot will perform the actions of the game server user via API.

The pgzero application will receive information from the game server via API and draw cats and coins in the right places. Cats move around a field with conditional cells measuring 32x32 pixels.

