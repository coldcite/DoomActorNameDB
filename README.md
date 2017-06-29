# DoomActorNameDB
ZDoom-compatible language file storing known actor classes and their proper names, ACS function to query included.

# How to use
- Add files to your project
- Include library "doomactornamedb" in your code
- Calling GetActorName(*strClassName*) will return the proper name for actor with class *strClassName* if found.

Unless otherwise noted, in case the DB is updated you will only need to update the language file.