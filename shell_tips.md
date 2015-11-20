### Shell Tips Summary
###### Songpeng Zu /zusongpeng@gmail.com/
###### 2015-11-15

Shell command and its script are quite useful when we use Linux system. This document summerize some tips on shell command or its script by the author.  

1. Use Shell script as the controller to control your different jobs, no matter they are written as R, Python, or C++.  
2. Use _screen_ to split the window, then differen windows can handle different jobs.  
  * ```C-a S-s``` create a new window horizontally
  * ```C-a c``` create a new shell
3. Vim is quite useful as the text editor, especially when you are on the remote cluster. 
  * Use vim to open the directory, then use Enter to open one file in current directry, and use Ctrl+^ to go back to the            directory.   
  * Use split and vsplit to open more files.
  * Use !shell-command to run temp shell command.
  * Use :vertival resize +/- _num_  to control the window size.

4. Use _grep_ -r /pattern/ * to search all the lines in all the file in current directory containning the patter.  
