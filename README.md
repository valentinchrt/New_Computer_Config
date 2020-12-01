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
Install Mac App Store softs via Homebrew (Dashlane, Slack, Paste, Endel, Contrast, Messenger, Telegram)

```
mas install 552383089 803453959 967805235 1484348796 1254981365 1480068668 747648890
```

### Main softs
Install main softs via [cask](https://caskroom.github.io/search)

```
brew cask install cleanshot kap spectacle alfred appcleaner google-chrome flux vlc webtorrent whatsapp dropbox spotify molotov
```

### Work softs
Install work softs via [cask](https://caskroom.github.io/search)

```
brew cask install slack zoom figma visual-studio-code iterm2 airtable notion loom pitch sketch zeplin abstract
```

### Install Aerial+Fliqlo Screensavers
Aerial is a Mac screensaver based on the new Apple TV screensaver that displays the Aerial movies Apple shot.
Fliqlo is a clock screensaver that allows you to make your desktop/laptop device screen look like a flip clock.

```
brew cask install aerial fliqlo
```

📝 To update all outdated app installed via homebrew: `brew update && brew upgrade`
