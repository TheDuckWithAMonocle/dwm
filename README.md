# Duckwithamonocle's DWM fork. 

A DWM fork with all of the basic features added in, so anyone migrating from another Tiling manager can just simply use it. 

## How do i use it? 

Thanks to the suckless ideology, everyone has their own fork, and is required to build their forks themselves. It's not hard, and it's great! 

Adding DWM to your greeter by make a file called DWM.desktop and in the directory `/usr/share/xsessions`:

 ```[Desktop Entry]
    Encoding=UTF-8
    Name=Dwm
    Comment=Dynamic window manager
    Exec=dwm
    Icon=dwm
    Type=XSession
 ```
Building:

```cd ~/dwm && make```

Now, as root:

``` make install```

Done!

Exit to your greeter by pressing `Ctrl + Shift + Q` 

