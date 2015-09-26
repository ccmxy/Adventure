# adventure
This is an adventure game written in C in which 7 rooms are randomly chosen from 10, 
and each of those 7 rooms is connected to somewhere between 3 and 6 other rooms. 
It is not possible to reach a dead end. 

#From terminal in a linux machine:
Simply type "adventure" to run the exectable file. You will be presented with a list of 
your current location and a list of rooms that are connected to it. Try to get to the final room,
which is different each time. 
 
After you have played the game, you will find in your directory a folder called minorc.adventure.[the process id from when you played the game]

This folder will contain 7 files, which will be the names of the chosen rooms, and in each file you will find
the names of each room that it is connected to. Since the rooms have spaces in the names you should put quotes
around them to view their contents, like 

`cat "Garden of Knowledge"`


If you want to make the executable file yourself, type

`gcc -o [what you want to call executable file] adventure.c`
