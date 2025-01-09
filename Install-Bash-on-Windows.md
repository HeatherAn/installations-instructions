# Install Bash on Windows

In order to install Bash on Windows you need to install **Git** in your work laptop/station.

-	Download the **Git** for [**Windows installer**](https://gitforwindows.org/).    
-	Run the installer:  
    1.	Click on **Next** until **Choosing the default editor used by Git**. From the dropdown menu ensure **Use Vim (the ubiquitous editor) as Git's default editor** is selected and click on **Next**. **Vim** is a text editor. You can change this choice later on with `git config`.  
    2.  In **Adjusting the name of the initial branch in new repositories** ensure that **Let Git decide** is selected and click **Next**.   
    3.	In **Adjusting your PATH environment** ensure that **Git from the command line and also from 3rd-party software** is selected and click **Next**. 
    4.	In **Choosing the SSH executable** ensure that **Use bundled OpenSSH** is selected and click **Next**.  
    5.	In **Choosing HTTPS transport backend** ensure that **Use the native Windows Secure Channel library** is selected and click  **Next**.  
    6.	In **Configuring the line ending conversions** ensure that **Checkout Windows-style, commit Unix-style line endings** is selected and click **Next**.  
    7.	In **Configuring the terminal emulator to use with Git Bash** ensure that **Use MinTTY (the default terminal of MSYS2)** is selected and click **Next**.  
    8.	In **Choose the default behaviour of `git pull`** ensure that **fast-forward or merge** is selected and click **Next**.  
    9.	In **Choose a credential helper** ensure that **Git Credential Manager** is selected and click **Next**.   
    10.	In **Configuring extra options** ensure that **Enable file system caching** is selected and click **Next**.  
    11.	Click on **Install**.   
-	In order to run Git smoothly it is highly recommended you have an explicit `HOME` environment variable in your system. In order to check 
whether `HOME` has been set or not, open Git Bash and type `echo $HOME`. Your home directory will be printed to the terminal (e.g. `/c/Users/your_username`). If your `HOME` environment variable is not set:  
    1.	Open the Windows command prompt (open `Start Menu` on your Windows, then type `cmd` and press `Enter`).  
    2.	Type the following line into the command prompt window: `setx HOME "%USERPROFILE%"`  
    3.	Press `Enter`. You should see `SUCCESS: Specified value was saved`.  
    4.  Quit the command prompt by typing `exit` and pressing `Enter`.  
    5.  Close the Git Bash and open it again and type `echo $HOME`. You should now be able to see the value of the `HOME` variable (your home directory).  


___________________________

[Previous : README](https://github.com/HeatherAn/installations-instructions/blob/main/README.md)  
[Next     : Install Git on Windows](https://github.com/HeatherAn/installations-instructions/blob/main/Install-Git-on-Windows.md)

[Go back to README](https://github.com/HeatherAn/installations-instructions/blob/main/README.md)  