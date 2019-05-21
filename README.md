# My machine setup

## macOS

### Screenshot locations

```bash
defaults write com.appple.screencapture location ~/Downloads
killall SystemUIServer
```

### Mac App Store

* https://itunes.apple.com/gb/app/magnet/id441258766?mt=12
* https://itunes.apple.com/gb/app/flycut-clipboard-manager/id442160987?mt=12
* https://itunes.apple.com/gb/app/just-color-picker/id886547068?mt=12
* https://itunes.apple.com/gb/app/the-unarchiver/id425424353?mt=12

### Homebrew

Install
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Packages:
```bash
brew install go	nvm
```

Casks:
```bash
brew cask install adobe-acrobat-reader       qlmarkdown                 visual-studio-code
brew cask install chromium                   sourcetree                 zoomus
brew cask install docker                     iterm2
```
