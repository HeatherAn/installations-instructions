# Install VSCode on Windows

1. Download the [**Visual Studio Code installer for Windows**](https://code.visualstudio.com/download).   
2. Run the installer (`VSCodeUserSetup-{version}.exe`).  
3. In **Select Additional Tasks** make sure **Add to PATH (requires shell restart)** option is selected.  
4. By default, VSCode will be installed under `C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code`.   

In order to verify VSCode has been added to your `PATH` environment variable, go to Git Bash and type `code`. This should launch VSCode.

### Install the following VSCode Extensions

Install the following VScode extensions:

* Git Graph 
* GitLens
* Python
* Code Spell Checker
* Remote - SSH
* Remote Development
* Live Share

You can follow the instructions [here](https://code.visualstudio.com/docs/editor/extension-marketplace) on how to (un)install VSCode extensions.  

Note: you can also have VSCode if you install Anaconda (in case of interest see [here](https://docs.anaconda.com/anaconda/install/windows/))

### Ensure Git Bash is the default terminal

In VSCode:  

- Open a terminal by going to the top menu: `Terminal` > `New Terminal`  
- At the top right corner of the terminal, next to the `+` sign, there will be a drop down menu. Make sure to select **Git Bash** (**Git Bash** has to be already installed in the system and added to the `PATH` environment variable). If **Git Bash** is not shown as default, you can set it by selecting from the drop down menu `Configuration Terminal Settings`. In User Features look for `Terminal > Integrated > Default profile: Windows`. Select **Git Bash** from the drop down menu. Then **Git Bash** will be the default terminal within VSCode.  

___________________________

[Previous : Install Make on Windows](https://github.com/HeatherAn/installations-instructions/blob/main/Install-Make-on-Windows.md)  

[Go back to README](https://github.com/HeatherAn/installations-instructions/blob/main/README.md)  