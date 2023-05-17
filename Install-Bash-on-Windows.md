# Install Bash on Windows

In order to install Bash on Windows you need to install **Git** in your work laptop/station.

-	Download the **Git** for [**Windows installer**](https://gitforwindows.org/).    
-	Run the installer:  
    1.	Click on **Next** four times (two times if you've previously installed Git).   
    2.	From the dropdown menu select **Use Vim (the ubiquitous editor) as Git's default editor** and click on **Next**. **Vim** is a text editor. You can change this choice later on.  
    3.  On the page that says "Adjusting the name of the initial branch in new repositories", ensure that **Let Git decide** is selected.   
    4.	Ensure that **Git from the command line and also from 3rd-party software** is selected and click on **Next**. 
    5.	Ensure that **Use bundled OpenSSH** is selected and click on **Next**.  
    6.	Ensure that **Use the native Windows Secure Channel library** is selected and click on **Next**.  
    7.	Ensure that **Checkout Windows-style, commit Unix-style line endings** is selected and click on **Next**.  
    8.	Ensure that **Use MinTTY (the default terminal of MSYS2)** is selected and click on **Next**.  
    9.	Ensure that **Default fast-forward or merge)** is selected and click on **Next**.  
    10.	Ensure that **Git Credential Manager** is selected and click on **Next**.   
    11.	Ensure that **Enable file system caching** is selected and click **Next**.  
    12.	Do not select any experimental option, just click **Next**.  
    13.	Click on **Install**.  
    14.	Click on **Finish** or **Next**.  
-	If your `HOME` environment variable is not set (or you don't know what this is):  
    1.	Open the Windows command prompt (open `Start Menu` on your Windows, then type `cmd` and press `Enter` key)  
    2.	Type the following line into the command prompt window exactly as shown: `setx HOME "%USERPROFILE%"`  
    3.	Press `Enter` key. You should see `SUCCESS: Specified value was saved`.  
-	Quit the command prompt by typing `exit` and pressing the `Enter` key.  


___________________________

[Previous : README](https://github.com/HeatherAn/installations-instructions/blob/main/README.md)  
[Next     : Install Git on Windows](https://github.com/HeatherAn/installations-instructions/blob/main/Install-Git-on-Windows.md)

[Go back to README](https://github.com/HeatherAn/installations-instructions/blob/main/README.md)
