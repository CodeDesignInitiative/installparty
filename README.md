# Installing software for the Code+Design Camp

## Mac

To install all the basic and advanced tools for coding and designing, we will use the package manager `homebrew` that will make it possible to install software with typing text. Many coding tools can only be installed this way - and not via _App Store_ or downloading a `*.dmg` from a website.


### How to install Homebrew?

- Open `Terminal` (`cmd+space+terminal`)
- You can type in the first line (just as in Word) (this is called `command line`)
- Copy the text `xcode-select --install` to the line and hit `Enter` 
- A software update popup window will appear. Click `Install` (or the equivalent in your language)
- This will install `Command Line Tools` that are necessary to install `Homebrew`. Caution: This may take up to 1 hour, but you can continue working on your computer
- Once the download is done, you can install `Homebrew` with the following command
- Copy the following text to the command line and hit `Enter`:  
`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` 
- The installation script will ask for your admin password: This is the password you use to log into your computer. Attention: When you type your password, you will not see every character on the command line. This is for security reasons!
- Once the installation is done, type `brew` and hit `Enter` and you can see an explanation of what `brew` can do
- You are now ready to install programs!


### How to install the software for the camp?

- Open your terminal (see above)
- You will install the following desktop software:
    - `Google Chrome` (or the open source equivalent `Chromium` if you don't trust Google)
    - `Firefox Developer Edition` (always a bit newer than the normal Firefox)
    - `Visual Studio Code` (an open source text editor, do not confuse with the big Visual Studio)
- To install these desktop software, copy `brew install google-chrome firefox-developer-edition visual-studio-code` and hit `Enter`
- We will also install `NodeJS`. You can use this, to run *JavaScript* on your computer
- Copy the text (or type) `brew install node` and hit `Enter`


### How to install even more applications for coding and designing?

- `brew cask install inkscape`: Illustration software (Open Source alternative to _Adobe Illustrator_)
- `brew cask install blender`: 3D modelling
- `brew cask install gimp`: Photo editing (Open Source alternative to _Adobe Photoshop_)