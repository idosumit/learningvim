# Learning Vim

A repository for storing my vim & vimscript study notes.

#

## Current ongoing/s:

### Neovim

Currently doing the [kickstart.vim](https://github.com/idosumit/kickstart.nvim) repository's `Tutor`.

#### Learnings

- Moving
  - `w`: Go to the start of the next word (excludes the first character of that word).
  - `e`: Go to the end of the current word (includes the last character).
  - `$`: Go to the end of the line, including the last character.
  - `2w`: Move the cursor 2 words forward.
  - `3e`: Move the cursor to the end of the 3rd word forward from the current word.
  - `0`: Go to the start of the line.

- Deleting
  - `x`: Delete the character that the cursor is resting on (in normal mode)
  - `d`+`d`: Delete the entire line.
  - `dw`: Delete the word that the cursor is resting on (the cursor HAS to be at the beginning of the word)
  - `d$`: Delete whatever it is to the end of the line.
  - `2d`: Delete 2 lines.

- Copying & Pasting (steps)
  > Note: `v` is visual mode and `V` is visual line mode.
  1. Press `v` or `V` & move the cursor to the end of where I wanna copy or cut. _(There's also the `<ctrl>+v` option to enter visual block mode. but I think it's not as important to me, personally.)_
  2. Press `y` to copy or `d` to cut.
  3. Take the cursor wherever I wanna paste and press `P`.

---

## Additional Materials

- Practical Vim: Edit Text at the Speed of Thought (this is a book)
  - Chapter ...

- [Learn-Vim](https://github.com/iggredible/Learn-Vim)
  - [Website version of this repo](https://learnvim.irian.to/)
