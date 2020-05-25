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
- Movement in a line to a particular character ```t (or f) + character```  
- Move to first word in the line ```0 + w```
## Selecting a block of text
- Selecting blocks with entire line selected ```Shft + v + movement_command(optional)```
- Selecting blocks of text with entire line not selected at once ```Ctrl + v + movement_command(optional)```
## General Editing
- Copy selection ```Selection + y```
- Paste selection ```p```
- Delete selection ```selection + d```
(Note: delete selection places copied contents to clipboard hence they can be used in copy paste operations as well)
(Note: ```d + d``` removes the entire line on which the cursor is)
- Undo ```u```
- Redo ```Ctrl + r```
## General Search
- To search for a word in a file```/ + word``` ( Note: To keep searching for next occurence of this word, ```n``` and to stop at a particular occurence ```Enter```)
(Note: if you want to search for word under the cursor, ```*``` can be used to go to next occurence of that particular workd)
## General Rules
- Place a number before a command and that command will be repeated by that number of times . Eg. ```3 + d + d``` should remove 3 lines
- Repeat the last entered command ```.```
- Upper case and lower case character commands can help a lot. For eg. ```p``` is to paste below the cursor and ```P``` is to paste above cursor. ```o``` is add a line below cursor and ```O``` is to add a line above cursor.
