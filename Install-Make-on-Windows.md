# Install Make on Windows

To install **make** in Windows Git-Bash:

- Go to https://sourceforge.net/projects/ezwinports/files/  
- Click on the file `make-4.3-without-guile-w32-bin.zip` and the download will start automatically.    
- Go to the directory where the zip file has been downloaded. Unzip the file. You can do this with the terminal by typing: `unzip make-4.3-without-guile-w32-bin.zip`  
- When unzipped, you will see 4 new directories: `bin`, `include`, `lib` and `share`.   

    - `bin` directory has a `make.exe` file in it   
    - `include` directory has a `gnumake.h` file in it  
    - `lib` directory has a `libgnumake-1.dll.a` file in it   
    - `share` directory has 3 sub-directories in it: `doc`, `info` and `man`    
        - `doc` directory has a `make-4.3` sub-directory with a `NEWS` file   
        - `info` directory has 3 files: `make.info`, `make.info-1` and `make.info-2`   
        - `man` directory has 2 sub-directories: `cat1` and `man1`   
            - `cat1` has a `make.1` file   
            - `man1` has a `make.1` file   

Now you will have to copy the contents of each one of those directories to the respective directory (named the same) where `git` is installed. For this first do: `where git`. This will show you *where* the `git.exe` is in your device. You will probably see more than one directory path prompted to the screen of the terminal. Look for the directory path that has `Git\mingw64\bin` in it. Let us say this is `~/AppData/Local/Programs/Git/mingw64/bin/git.exe`. Then go to the `~/AppData/Local/Programs/Git/mingw64` directory by doing:  

```
    cd ~/AppData/Local/Programs/Git/mingw64
    ls
```

Explore that directory. You will see that there there are several ones, among which you find a `bin`, `include`, `lib` and `share` directory. If you do not see one of them you can create them with `mkdir`. For example `mkdir include`.

- We will now copy the contents of the unzipped **make** `bin`, `include`, `lib` and `share` folders, into the **Git/mingw64** `bin`, `include`, `lib` and `share` respective folders. **Do NOT overwrite nor replace any existing files!** That is why it is important you first explore what there is in the `~/AppData/Local/Programs/Git/mingw64` directory. 

Go with the `cd` command to the directory where you unzipped the .zip file (e.g., `cd ~/Downloads`). We will now copy the files one by one to the respective `~/AppData/Local/Programs/Git/mingw64` directory:

```
    cd Downloads
    cd bin
    cp make.exe ~/AppData/Local/Programs/Git/mingw64/bin
    cd ..
    cd include
    cp gnumake.h ~/AppData/Local/Programs/Git/mingw64/include
    cd ..
    cd lib
    cp libgnumake-1.dll.a ~/AppData/Local/Programs/Git/mingw64/lib
    cd ..
    cd share
    mv man/ ~/AppData/Local/Programs/Git/mingw64/share/
    cd doc
    mv make-4.3/ ~/AppData/Local/Programs/Git/mingw64/share/doc/
    cd ..
    mv info/ ~/AppData/Local/Programs/Git/mingw64/share/
    
```
- You can now go back to where you initially unzipped the file (e.g., `cd ~/Downloads`) and delete the zip file and all unzipped contents.
- Close the terminal and open it again, so that it now recognizes the **make** command.


___________________________

[Previous : Install Pip on Windows](https://github.com/HeatherAn/installations-instructions/blob/main/Install-Pip-on-Windows.md)  
[Next     : Install VSCode on Windows](https://github.com/HeatherAn/installations-instructions/blob/main/Install-VSCode-on-Windows.md)

[Go back to README](https://github.com/HeatherAn/installations-instructions/blob/main/README.md)
