# New_Computer_Config
List of things to do with a new computer

## ⚙️ Install environment

#### Homebrew
[Homebrew](https://brew.sh) installs the stuff you need that Apple (or your Linux system) didn’t.

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

#### Mas-cli
[mas-cli](https://github.com/mas-cli/mas) is a simple command line interface for the Mac App Store. Designed for scripting and automation.

```
brew install mas
```

## 📦 Install softs

### Mac App Store
Install Mac App Store softs via Homebrew (Dashlane, Slack, Paste)

```
mas install 552383089 803453959 967805235
```

### Main softs
Install main softs via [cask](https://caskroom.github.io/search)

```
brew cask install alfred appcleaner google-chrome flux vlc webtorrent whatsapp dropbox spotify molotov
```

### Work softs
Install main softs via [cask](https://caskroom.github.io/search)

```
brew cask install slack skype sketch figma visual-studio-code iterm2 zeplin airtable notion loom abstract
```

### Install Aerial Screensaver
Aerial is a Mac screensaver based on the new Apple TV screensaver that displays the Aerial movies Apple shot.

```
brew cask install aerial
```

📝 To update all outdated app installed via homebrew: `brew update && brew upgrade`
