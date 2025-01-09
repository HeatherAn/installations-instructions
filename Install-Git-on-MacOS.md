# Install Git on MacOS

## For more recent MacOS versions

If you are using MacOS 10.15 ("Catalina") or later, you 
will need to give **Full Disk Access** permissions to the **Terminal**. If you're using an earlier 
version of MacOS, you can skip this section and continue to the installation instructions.

- Depending on your MacOS, look for **System Preferences** or **Systems Settings** and open it.  
- Depending on your MacOS select either **Security and Privacy** or **Privacy & Security**.  
- Under **Privacy** look for **Full Disk Access** and select it.    
- Ensure full disk access has already been set for the **Terminal** application.    

## Installation instructions

Install Git on your Mac using one of the following methods:  

### Method 1

-  Open the **Terminal** application by using the Launchpad.  
-  Regardless of the default shell (which will probably be either **bash** or **zsh**) type `clang --version` and press `Return`.   
-  If you have **clang** already installed, you will see the clang version printed to the terminal. If **clang** is not installed, a window will pop up asking if you would like to install **Xcode Command Line Tools**. Follow the prompts to install them.   

### Method 2

- Open the **Terminal** application by using the Launchpad.   
- Type `xcode-select --install` and press `Return`.    
- A window will pop up asking if you would like to install **Xcode Command Line Tools**. Follow the prompts to install them.  

### Method 3

- Go to the [Apple developer website](https://developer.apple.com/xcode/).  
- Press the `Download` blue button at the top right corner of the screen, and select **Xcode**.      
- Install the latest version of **Xcode**. Be aware you may be prompted to log in with an **Apple Developer ID** (this is different than your **Apple ID**). Follow the instructions for creating an Apple Developer ID and use it to log into the site and continue the installation.  


## For older MacOS versions

For OS X 10.9-10.14, install **Git** by downloading and running the most recent "mavericks" installer from this [list](https://sourceforge.net/projects/git-osx-installer/files/). Because this installer is not signed by the developer, you may have to right click (**control** click) on the `.pkg` file; click **Open**; and click **Open on the pop up window**.  

For older versions of OS X (10.5-10.8) use the most recent available installer labelled "snow-leopard" available [here](https://sourceforge.net/projects/git-osx-installer/files/).  


## Verify

- Open the **Terminal** application by using the Launchpad.  
- Type `git --version` and press `Return`. You should see a message reporting the version of Git.


________________________

[Previous : Install Bash on MacOS](https://github.com/HeatherAn/installations-instructions/blob/main/Install-Bash-on-MacOS.md)  
[Next     : Install Python on MacOS](https://github.com/HeatherAn/installations-instructions/blob/main/Install-Python-on-MacOS.md)  

[Go back to README](https://github.com/HeatherAn/installations-instructions/blob/main/README.md)  