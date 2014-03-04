.ultimate
========

*.ultimate* is the ultimate way to sync development environment configurations between your OS X and Linux machines!

Common Scenario & Problem: You have to work from multiple machines, but you hate always having to reconfigure each of your development environments every time you add/remove/update configurations.  
Solution: Use *.ultimate* and stop struggling to manage all of your machines separately; instead make them work in unison.  
  
With *.ultimate* you can install and sync all of your packages, scripts, and configurations fast and easily.  

### Is this for me?
If you are tired of trying to keep all of your configurations the same across all devices, then this is for you!  
*.ultimate* can be used in various applications, but it was built to shine using:
    * Vim (MacVim/Gvim)
    * spf13-vim distribution

### Features
    * Incredibly easy to use, fast to get up and running
    * Integrates and implements the power of git, so you can:
        * Revert to earlier configurations
        * Use hooks to automatically update all computers on a push.
        * and more...!
    * Install any third-party packages, distributions, and extensions
    * Easily update/upgrade packages (if available by package author)

### Getting started

#### Supported OS:  
    * OS X >= 10.6
    * Linux (Debian based only), only tested on Ubuntu 12.04+

#### Dependencies:  
To get the most out of *.ultimate* we require a few dependencies.  
    * Git
    * Mac: Homebrew (Sorry MacPorts fans...)

We have a built in dependency installer in case you don't already have them.  Getting up and running is fast and easy!  

#### Usage:  
1. Fork this repository and clone the fork to your home directory (~)  
2. Run the following command in your terminal:  
    * `cd ~/.ultimate && sudo chmod +x ultimate && ./ultimate welcome`
3. Follow the welcome screen and familiarize yourself with the commands.
4. Add any packages, scripts, or configurations to *ultimate* using the command `ultimate install`
5. Push your environment to git using `ultimate push`
4. Congrats, now you are ready to easily integrate your environment across machines!

