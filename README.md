# New_Computer_Config
List of things to do with a new computer

#### BetterTouchTool license & backup + Tower license + Sketch license

#### Things to install:
- Install [Homebrew](http://brew.sh/)
	- `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
- Install tools
	- [Homebrew Cask](https://caskroom.github.io/) `brew tap cask/cask`
- Install [QuickLook Plugins](https://github.com/sindresorhus/quick-look-plugins)
	- `brew cask install qlcolorcode qlstephen qlmarkdown quicklook-json betterzip qlimagesize webpquicklook qlvideo`
- [Install main softs](https://caskroom.github.io/search)
	- `brew cask install alfred google-chrome slack firefox skype sketch visual-studio-code iterm2 flux bettertouchtool zeplin appcleaner vlc figma airtable notion loom abstract`
- Install Mac App Store Softs (Sip, iA Writer, The Unarchiver, Paste 2)
	- `mas install 507257563 775737590 425424353 967805235`
- Update Potential outdated App Store apps such as Xcode
	- `mas upgrade`
- [Google Chrome Canary](https://www.google.fr/chrome/browser/canary.html)
- [Meta](https://www.nightbirdsevolve.com/meta/updates/latest/)
- [Loom](https://www.loom.com/desktop)
- [EasySubs](https://tucci.me/projects/easysubs/)
- [Tempo](https://www.yourtempo.co/)
- [svgo-gui](http://goo.gl/0Qu9B)
- [Paste Helper](https://pasteapp.me/helper/)

📝 To update all outdated app installed via homebrew: `brew update && brew upgrade`

#### Todo
- Add BetterTouchTool, Flux, Mega at startup
- Set VisualStudio Code $PATH as explained [here](https://stackoverflow.com/a/29971430/3906770):
After installation, launch VS Code. Now open the Command Palette (F1 or ⇧⌘P on Mac) and type shell command to find the Shell Command: Install 'code' command in PATH command.
- Log in npm through the CLI : `npm login`
- Do this to automatically set the corresponding NPM version when you enter a project: https://github.com/nvm-sh/nvm#zsh
- Enable the `z` plugin for `zsh` by adding it in the plugins like so in the `.zshrc` file: `plugins=(git z)`
- Change keyboard key repeat rate to make it faster : System Preferences => Keyboard => Key Repeat Rate
- Disable sound effects for Paste
