![Python Versions](https://img.shields.io/static/v1?label=python&message=3.6%20|%203.7%20|%203.8&color=orange)

# Textris

A text-based, colorful tetris implementation.
The challenge was to code a game of tetris without using any non-default libraries and by displaying everything through console.

## Run it

![Launch demo gif](/images/textris_launch_demo.gif?raw=true)

Download/clone textris.py and run it inside CMD or your favorite ANSI-compatible terminal. (only tested on Windows)
```console
$ python textris.py
```
Python version: **Python 3.6 or higher**\
No additional packages/requirements needed!

## Controls

- D: move right
- A: move left+
- S: "soft" drop
- W: hard drop
- Right Arrow: rotate right
- Left Arrow: rotate left
- Space: hold piece

## Score saving

Scores are saved in a custom file named scores located in the shell's current work directory.
To disable score saving and loading, change the SAVESCORE variable in textris.py.

```python
SAVESCORES = False
```

## Media
![Menu](/images/textris-1.png?raw=true)
![Gameplay](/images/textris-2.png?raw=true)
![Scores](/images/textris-3.png?raw=true)
