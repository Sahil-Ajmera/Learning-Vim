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
- Move to end of next word in line ```e```
- Move to the beginning of line ```0```
- Move to the end of line (Puts into INSERT mode after)```Shft + a```
- Move to the beginning of file ```g + g```
- Move to the end of file ```Shft + g```
- Movement in a line to a particular character ```t (or f) + character```  
- Move to first word in the line ```0 + w```
## Selecting a block of text
- Selecting blocks with entire line selected ```Shft + v + movement_command(optional)```
- Selecting blocks of text with entire line not selected at once ```Ctrl + v + movement_command(optional)```
- Capture from cursor to end of line ```$```
## General Editing
- Copy selection ```Selection + y```
- Paste selection ```p```
- Delete a character ```x```
- Delete selection ```selection + d```
(Note: delete selection places copied contents to clipboard hence they can be used in copy paste operations as well) (Note: Commands like ```d + w``` can be used to delete a word)
(Note: ```d + d``` removes the entire line on which the cursor is)
- Replace a character ```r + replacement_characeter```
- Change ```c```(Note: changes the word and puts you in INSERT mode) (Note: Can be used in commands like ```c + w``` to change word)
- Undo ```u```
- Redo ```Ctrl + r```
## General Search
- To search for a word in a file```/ + word``` ( Note: To keep searching for next occurence of this word, ```n``` and to stop at a particular occurence ```Enter```)
(Note: if you want to search for word under the cursor, ```*``` can be used to go to next occurence of that particular workd)
## General Search and replace
- To replace a word in the entire file without asking```:%s/oldstring/newstring/g```
- To replace a word in the entire file with asking ```:%s/oldstring/newstring/gc```
- To replace a word in a set of lines ```:3,9s/oldstring/newstring/g```
## Macros
- To start a macro ```q + char```
- To stop recording ```q```
- To play macro ```@char```
## Programming
- To navigate to another file ```Ctrl + p```
- To get auto completion ```Ctrl + Space```
- To go to definition ```, + d```
- Folding functions ```f``` at function or ```Shift + f``` to fold all functions in file.
- Look at opening closing bracket combinations in a line ```%```
## General Rules
- Place a number before a command and that command will be repeated by that number of times . Eg. ```3 + d + d``` should remove 3 lines
- Repeat the last entered command ```.```
- Upper case and lower case character commands can help a lot. For eg. ```p``` is to paste below the cursor and ```P``` is to paste above cursor. ```o``` is add a line below cursor and ```O``` is to add a line above cursor.
- To execute a command without going to terminal ```!command```
