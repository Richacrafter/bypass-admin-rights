# Welcome to bypass-admin-rights!

(EDUCATIONAL PURPOSES ONLY)

This program lets you bypass UAC on Windows 10 (older versions only!)

(!) Unfortunately, this no longer works as of 2021 April 19. It may work for a very little amount of applications, but that's it. 

If you are on older version of Windows 10, you can still use this trick.

EXPLANATION:

The code is very simple:

cmd /min /C "set __COMPAT_LAYER=RUNASINVOKER && start "" "%1"

cmd /min /C : is code to run in cmd.

set __COMPAT_LAYER=RUNASINVOKER : run app as Admin without Admin.

 && start "" "%1" : start at the location of opened (dragged) file.

 USAGE/TUTORIAL:

 Drag your file with the shield icon on the bat file and run it!


 IF YOU HAVE ISSUES PLEASE TYPE IN ISSUES TAB.
