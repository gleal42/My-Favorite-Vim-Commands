# My-Favorite-Vim-Commands

## .vimrc

- set nu rnu
- set si
- syntax on

## Buffers

- vim * select all files from outside vim
- next * select all files from inside vim
- :e file.c
- b fi[tab]
- wa save all buffers
- waq save all buffers and exit

## Search for words

- / n N -> search for specific words
- * and # -> search for word under cursor

## Split Windows

- vs
- sp
- :vert sb f[tab]
- ctrl-w x -> Swap windows
- ctrl-w l -> Go to right window
- ctrl-w h -> Go to left window
- ctrl-w r -> Rotate windows
- ctrl-w R -> Rotate opposite way
- ctrl-w = -> Resize windows same size
- ctrl-w + -> Resize window bigger
- ctrl-w - -> Resize windows smaller

:bufdo do something in all buffers



## Selection

- shift v -> select whole line
- ctrl v -> Select in blocks
- Shift i esc esc write something in multiple lines

- viw -> select word
- va" -> select everything inside quotes including quotes

- vt letter -> select everything from cursor to letter (not including letter)
- vf letter -> select everything from cursor to letter (including letter)

## Navigation select mode

- hjkl
- w word forward
- W full word forward
- e end of word
- E end of full word
- b word backward
- B full word backward
- 0 start of line
- $ end of line
- gg start of file
- G end of file
- % go to matching bracket ({
- H cursor at top of page
- L cursor at bottom of page
- M cursor at middle of page
- 55 G go to line 55
- 55 | go to line 55 in sentence

- ctrl i -> go to previous location
- ctrl o -> go to next location

## Visibility

- zz ajust window so cursor is in middle of screen
- Ctrl d Scroll down half page
- Ctrl u Scroll up half page

## Macros

- q letter -> record macro
- @ letter -> use macro
- @@ -> use prev macro

## Productivity

- . -> repeat last thing written
- ctrl n -> autocomplete with things from document
- Select U -> Upper case letters
- Select u -> Lower case selection
- %s/pattern/subst/gce replace, ignore errors and ask permission for each replacement
- u undo
- ctrl r redo
- 4 j -> go down 4 lines

## Writing

- i write in cursor
- a write one letter after cursor
- I write beggining of line
- A write end of line
- o write line below
- O write line above
- d delete selection
- c delete selection and switch to writing mode
- x delete under cursor
- r replace letter
- y copy
- p paste
- dd delete line and copy

## Other interesting

- :Ex -> Directory mode
- vimgrep pattern files (e.g. *)
- cn - jump to the next match.
- cN - jump to the previous match.
- clist - view all the files that contain the matched string
- cc number - jump to specific match number, which you get from :clist output.
- :set hlsearch
- :noh -> clear highlights
