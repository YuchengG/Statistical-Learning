### Shell Tips Summary
###### Songpeng Zu /zusongpeng@gmail.com/
###### 2015-11-15

Shell command and its script are quite useful when we use Linux system. This document summerize some tips on shell command or its script by the author.

1. Use Shell script as the controller to control your different jobs, no matter they are written as R, Python, or C++.
2. Use _screen_ to split the window, then differen windows can handle different jobs.
  * ```C-a S-s``` create a new window horizontally
  * ```C-a c``` create a new shell
  * ```C-a t``` or ```C-a C-i``` jump between the windows
  * ```C-a :resize 10``` resize current window horizontally defaut
3. Vim is quite useful as the text editor, especially when you are on the remote cluster.
  * Use vim to open the directory, then use ```Enter``` to open one file in current directry, and use ```Ctrl+^``` to go back.
    If ```Ctrl+^``` not work, try ```:e#n```, n=1,2,3... to jump to previous files.
  * Use ```:split``` and ```:vsplit``` to open file in new window, then use ```C-w C-w``` Jump between windows.
  * Use ```!shell-command``` to run temp shell command.
  * Use ```:vertival resize +/- _num_```  to control the window size.
4. Use _grep_ -r /pattern/ * to search all the lines in all the file in current directory containning the patter.
5. EMACS is another quite useful editor (in fact, it is not only an text editor.)
  * Use _evil_ package to involve vim innner emacs.
  * Use _term_ mode as the same Linux terminal, especially work for ssh to other remote clients.
    Use ```Ctrl-c Ctrl-j``` to jump to the line mode, in which you can use traditional emacs command, like ```M-```.
    Use ```Ctrl-c Ctrl-k``` to jump to the char mode, which is just the Linux terminal like.
  * Use _shell_ mode to open a shell communication mode in Emacs.
  * Use _dired_ mode to organize the directory.
