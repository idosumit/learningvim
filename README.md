# Learning Vim

A repository for storing my vim & vimscript study notes.

#

## Learnings

#### Moving

- `w`: Go to the start of the next word (excludes the first character of that word).
- `e`: Go to the end of the current word (includes the last character).
- `$`: Go to the end of the line, including the last character.
- `2w`: Move the cursor 2 words forward.
- `3e`: Move the cursor to the end of the 3rd word forward from the current word.
- `0`: Go to the start of the line.

#### Deleting

- `x`: Delete the character that the cursor is resting on (in normal mode)
- `d`+`d`: Delete the entire line.
- `dw`: Delete the word that the cursor is resting on (the cursor HAS to be at the beginning of the word)
- `d$`: Delete whatever it is to the end of the line.
- `2d`: Delete 2 lines.

#### Copying & Pasting (steps)

> Note: `v` is visual mode and `V` is visual line mode.

1. Press `v` or `V` & move the cursor to the end of where I wanna copy or cut. _(There's also the `<ctrl>+v` option to enter visual block mode. but I think it's not as important to me, personally.)_
2. Press `y` to copy or `d` to cut.
3. Take the cursor wherever I wanna paste and press `P`.

## Some nifty tricks

#### Marking

(via stackoverflow)

In command-mode, press m[letter]. For example, ma sets a mark at the current line using a as the mark identifier.

To get back to the mark press ' [letter]. For example, 'a takes you back to the line mark set in step 1. To get back to the column position of the row where you marked the line, use `a (back-tick [letter]).

To see all of the marks that currently set, type :marks.

#### Going back and forth from definitions

`gd` is always good for going to the definition, and followed by `CTRL+O` and `CTRL+I` for jumping back and forward.

---

## Additional Materials

- [Learn-Vim](https://github.com/iggredible/Learn-Vim)
  - [Website version of this repo](https://learnvim.irian.to/)
