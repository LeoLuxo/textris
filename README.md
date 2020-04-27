# Textris

A text-based, colorful tetris implementation.
The challenge was to code a game of tetris without using any non-default libraries and by displaying everything through console.

## Run it

Download/clone textris.py and run it inside CMD or your favorite ANSI-compatible shell. (only tested on Windows)
```bash
python3 textris.py
```
No additional modules/libraries needed!

## Controls

- D: move right
- A: move left
- S: "soft" drop
- W: hard drop
- Right Arrow: rotate right
- Left Arrow: rotate left
- Space: hold piece


## Score saving

Scores are saved in a custom file named scores.tetris located in the shell's work current work directory.
To disable score saving and loading, change the SAVESCORE variable in textris.py.

```python
SAVESCORES = False
```