# Text Adventure Games!
<br>

> **⚠️Text Adventure Games' Specifics:** This README is a general, big picture overview.
> - For more information on the specifics (game, playthrough, map, etc.) of each text adventure game (Cat Revenge game & Action Castle game), please visit the **README.md in the homeworks directory**.
> - For the parser go to text_adventure_games/parsing.py.
> - For the games' set up/components (action, blocks, and things) go to the respectively named directories in text_adventure_game.

<br>

This Python notebook builds a simple text adventure game inspired by the
[Adventuron Classroom](https://adventuron.io/classroom/) design by Chris
Ainsley of Adventuron Software Limited.

The main components are:
1. __The parser__, which interprets the player's commands.
2. __The game__, which represents world (a collection of __locations__,
   __items__, and __characters__), and describes what the player sees.
3. __The data__, which you input to create your own unique game.

<br> In the **homeworks** directory, there is...
- An implementation of an original text adventure game--Cat Revenge! (game, playthrough, map, etc.)
- And an implementation of the most classic text adventure game--Action Castle! (game, playthrough, map, etc.)

You can download a PDF of the Action Castle game from [Parsely: Preview n' Play Edition (this
contains a free copy the Action Castle game).](http://www.memento-mori.com/pdf/parsely-preview-n-play-edition) for more information.


## Environment Setup

First, clone the homework repo, create a virtual environment, and install
the dependencies.

```
$ git clone https://github.com/interactive-fiction-class/<repo name>
$ cd <repo name>/
$ python3 -mvenv venv
$ source venv/bin/activate
(venv) $ pip install .
```

### Graphviz

If you want to use the anything from `text_adventure_games.viz`, you will also need to install graphviz. There is both the graphviz app and the graphviz python library, which is a wrapper for the app.

We'll let the graphviz project explain how to do that: [graphviz.org/download/](https://graphviz.org/download/)

### Dev Environment Setup

If you are part of the dev team for this repo, use this pip command instead,
to do an editable install of this library, and to install the black code
formatter.

```
(venv) $ pip install -e .[dev]
```

## VSCode

We like to use VSCode, but you can use any editor you feel comfortable with.
The best way to ensure a good experience with VSCode is to launch it from the
project directory with your virtual environment already enabled.

```
$ cd path/to/homework/<repo name>/
$ source venv/bin/activate
(venv) $ code .
```

If the `code` command does not work, open VSCode's command pallet (command+shift+p)
and type `shell command`. VSCode should then show an option for installing
'code' in your PATH.


### The Traditional Way

For folks who prefer traditional Jupyter, or perhaps Jupyter Lab, launch the
Jupyter server from the homeworks directory and everything should work as you
expect.

```
$ cd path/to/homework/<repo name>/
$ source venv/bin/activate
$ cd homeworks/
$ jupyter notebook
```
