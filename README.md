# New_Computer_Config
List of things to do with a new computer

#### Get LastPass + AppStore passwords + (BetterTouchTool license + Tower license)

#### Things to install:
- Install [Homebrew](http://brew.sh/)
	- `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
- Install tools
	- `brew install git`
	- `brew install node`
	- `brew install mas`
	- `brew tap caskroom/cask`
- Install QuickLook Plugins
	- `brew cask install qlcolorcode qlstephen qlmarkdown quicklook-json betterzipql qlimagesize webpquicklook qlvideo`
- Install main softs
	- `brew cask install google-chrome slack firefox skype mamp sketch sublime-text iterm2 flux bettertouchtool tower transmit zeplin`
- Log In Mac App Store
	- `mas signin mas@example.com "password"`
- Install Mac App Store Softs (Sip, MPlayerX, Pages, iA Writer, The Unarchiver)
	- `mas install 507257563 421131143 409201541 775737590 425424353`
- Update Potential outdated App Store apps such as Xcode
	- `mas upgrade`
- [Google Chrome Canary](https://www.google.fr/chrome/browser/canary.html)

#### Update app autolaunch during system startup
- add BetterTouchTool at startup

#### Install via appStore
- iAWriter
- Sip

#### Install Sublime Text config
1) Install Package Manager and Open iTerm  
2) `cd /Users/louischenais/Library/Application\ Support/Sublime\ Text\ 3`  
3) `git init`  
4) `git remote add origin https://github.com/ChucKN0risK/st3-settings.git`  
5) `git fetch`  
6) `git checkout -t origin/master`  
7) Paste [these settings](https://gist.github.com/ChucKN0risK/1271219c30777d6f31d1)  
8) Create a `.bash_profile` in Username folder containing this [gist](https://gist.github.com/ChucKN0risK/f3052d944b074ff157b912fd197045c1)  
9) New sublime snippet from this [gist](https://gist.github.com/ChucKN0risK/777f52bc96b90087ab5998235be4d22c)
