# Learning-Vim
I share tips, tricks and learnings as I learn Vim and add a .vimrc file to follow.
## General Movement in a file
- Move up one line ```k```
- Move down one line ```j```
- Move left one character ```h```
- Move right one character ```l```
- Move to the next block of text ```Ctrl + ]```
- Move to the previous block of text ```Ctrl + [```
- Move to the next word in the line ```w```
- Move to the previous word in the line ```b```
- Move to the beginning of line ```0```
- Move to the end of line (Puts into INSERT mode after)```Shft + a```
- Move to the beginning of file ```g + g```
- Move to the end of file ```Shft + g```
- Movement by a number ```Number_of_lines + movement_command```
- Movement in a line to a particular character ```t (or f) + character```  
## Selecting a block of text
- Selecting blocks with entire line selected ```Shft + v + movement_command(optional```
- Selecting blocks of text with entire line not selected at once ```Ctrl + v + movement_command(optional)```

