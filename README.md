# AsciiHangman
A Hangman Game completely in the terminal with ascii arts.

## Description
This is a version of the very popular Hangman-Game. You try to guess a random word and if you make too much wrong guesses, your "Hangman" dies.
Hope you enjoy!

## Run

### Note:
The feature that the program clears the terminal screen may not work in every terminal. To disable it, go to the src/config.py file and edit the enableClearingTerminalScreen rule. You can do this with any text editor.

### Dependencies
First of all you need to have Python 3 installed.
The Program uses the modules `random` and `sys`. These should be preinstalled. Otherwise you can install them like this:
```commandline
python -m venv env
source env/bin/activate # On Windows env\Scripts\activate
```

```commandline
pip install pip --upgrade
pip install random
pip install sys
```
### Execute

#### Linux
If you are on any Linux distribution, just execute the start_hangman_bash.sh or start_hangman_zsh.sh file by typing `./start_hangman_bash.sh` or `./start_hangman_zsh.sh`

#### Others
To run the program, you only have to execute the `main.py`-File in the `src`-Folder. You can use the Terminal-Command `python src/main.py` or double click the file.
Make sure that you are in the project folder.

### Install
There's no compiled version of this but if this project get's more important for me, I'll think about giving an installation option.

## Errors, Fixes and more
If you notice any Errors, Bugs or weird things, just tell me by opening a new Issue on GitHub.
