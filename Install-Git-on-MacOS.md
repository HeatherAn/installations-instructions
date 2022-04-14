# For more recent MacOS versions

If you are using MacOS 10.15 ("Catalina"), 10.16 ("Big Sur), or 10.17 ("Monterey"), you 
will need to give "Full Disk Access" permissions to the Terminal. If you're using an earlier 
version of MacOS, you can skip this section and continue to the installation instructions.

- Open the **System Preferences** app   
- Select **Security and Privacy**   
- Select the **Privacy** tab   
- Click the **Padlock icon** in lower left-hand corner of the window. Enter your user name and password when prompted.  
- In the left-hand box, scroll down until you find **Full Disk Access** and select it    
- If the Terminal app is already listed in the right-hand box, check the box next to it. If the Terminal app isn't listed in the right-hand box, add it:   

    * Click the `+` icon under the right-hand box   
    * In the Applications menu, open the **Utilities** folder and select **Terminal.app**   
    * Click the **Open** button   
    * Locate Terminal in the right-hand box and check the box next to it  
    * Close **System Preferences**  

## Installation instructions

Install Git on your Mac using one of the following methods:  

### Method 1

-  Open the **Terminal** application by using the Launchpad or by browsing the Utilities folder found under Applications.  
-  Type `clang --version` and press `Return`   
-  A window will pop up asking if you would like to install **Xcode Command Line Tools**. Follow the prompts to install them.   

### Method 2

- Open the **Terminal** application by using the Launchpad or by browsing the Utilities folder found under Applications.  
- Type `xcode-select --install` and press `Return`    
- A window will pop up asking if you would like to install **Xcode Command Line Tools**. Follow the prompts to install them.  

### Method 3

- Go to the [Apple developer website](https://developer.apple.com/download/more/).    
- You will be prompted to log in with an **Apple Developer ID** (this is different than your **Apple ID**). Follow the instructions for creating an Apple Developer ID and use it to log into the site.  
- Download the latest version of **Command Line Tools** for **XCode** and install.  


# For older MacOS versions

For OS X 10.9 and higher, install **Git** by downloading and running the most recent "mavericks" installer from this [list](https://sourceforge.net/projects/git-osx-installer/files/). Because this installer is not signed by the developer, you may have to right click (**control** click) on the `.pkg` file; click **Open**; and click **Open on the pop up window**. 

For older versions of OS X (10.5-10.8) use the most recent available installer labelled "snow-leopard" available [here](https://sourceforge.net/projects/git-osx-installer/files/).


## Verify

- Open the **Terminal** application by using the Launchpad or by browsing the Utilities folder found under Applications   
- Type `git --version` and press `Return`   

You should see a message reporting the version number.


________________________

[Previous : Install Bash on MacOS](https://github.com/HeatherAn/installations-instructions/blob/main/Install-Bash-on-MacOS.md)  
[Next     : Install Python on MacOS](https://github.com/HeatherAn/installations-instructions/blob/main/Install-Python-on-MacOS.md)  

[Go back to README](https://github.com/HeatherAn/installations-instructions/blob/main/README.md)
