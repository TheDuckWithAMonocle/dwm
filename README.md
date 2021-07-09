# Duckwithamonocle's DWM fork. 

A DWM fork with all of the basic features added in, so anyone migrating from another Tiling manager can just simply use it. 
![screenshot](https://user-images.githubusercontent.com/87075822/125053460-c21eae80-e0c2-11eb-82e7-49eacac870e2.png)
## How do i use it? 

Thanks to the suckless ideology, everyone has their own fork, and is required to build their forks themselves. It's not hard, and it's great! 

Adding DWM to your greeter by make a file called DWM.desktopand in the directory `/usr/share/xsessions` and having the follwing text in the .desktop file:

 ```[Desktop Entry]
    Encoding=UTF-8
    Name=Dwm
    Comment=Dynamic window manager
    Exec=dwm
    Icon=dwm
    Type=XSession
 ```
After entering the DWM session, clone this repository. Follw the steps below to achive the setup I have. 

Building:

```cd ~/dwm && make```

Now, as root:

``` make install```

Done!

Exit to your greeter by pressing `Ctrl + Shift + Q`

## Autostarting 

This fork has the autostarting patch implemented. Just add ~/.dwm/autostart.sh and insert the programs you want to start on bootup in the file.

## Where did you get that background? 

I stole it from a redditor. 
No more questions, please. 


