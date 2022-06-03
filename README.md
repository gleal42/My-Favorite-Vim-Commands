# My Favorite Vim Commands

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
- ls to see list of all buffers

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

- ctrl-w shift L -> Send curr window to right
- ctrl-w shift H -> Send curr window to left

- ctrl-w = -> Resize windows same size
- ctrl-w + -> Resize window bigger
- ctrl-w - -> Resize windows smaller

- :bufdo do something in all buffers

#Window Navigation

:e .
50 ctrl-w <
set wfw

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
- \[ and { for paragraph navigation

## Visibility

- zz ajust window so cursor is in middle of screen
- Ctrl d Scroll down half page
- Ctrl u Scroll up half page

## Macros

- q letter -> record macro
- @ letter -> use macro
- @@ -> use prev macro

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
- ctrl d shift left writing mode
- ctrl t shift right writing mode
- shift >> shift right select mode
- shift << shift left select mode

## Other interesting

- :f or ctrl g to see name of curr file being edited
- :Ex -> Directory mode
- vimgrep pattern files (e.g. *)
- cn - jump to the next match.
- cN - jump to the previous match.
- clist - view all the files that contain the matched string
- cc number - jump to specific match number, which you get from :clist output.
- :set hlsearch
- :noh -> clear highlights
- - . -> repeat last thing written
- ctrl n -> autocomplete with things from document
- Select U -> Upper case letters
- Select u -> Lower case selection
- %s/pattern/subst/gce replace, ignore errors and ask permission for each replacement
- u undo
- ctrl r redo
- 4 j -> go down 4 lines
- ctrl o and ctrl i to go to previous locations and more recent
- crtl r 0 insert mode is same as p in visual


- ctrl w delete word (Imode)
- ctrl u delete line (Imode)

- ctrl v select numbers in line g ctrl a puts numbers in order

## Enter edit file under cursor
D delete file under cursor
R rename file under cursor
% create file in current directory

## Combos

- * + c + write + ESC + g + n => replace multiple letters then  . . . .  to repeat it

- ctrl v select columns -> Shift i -> write -> esc esc to write something in multiple lines
