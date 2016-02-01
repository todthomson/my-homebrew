# My-Homebrew

My Homebrew packages => http://brew.sh/

## Run the following

```sh
# confirm installation of xcode command line tools
xcode-select --install

# homebrew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew doctor
brew update

# cask
brew tap caskroom/cask

# prerequsites
brew install openssl

# useful tools
brew install wget

# zsh
brew install zsh zsh-completions
# TODO: Explain configuration...

# git
brew install git

# node (via nvm)
brew install nvm # and add as instructed to ~/.zshrc
nvm install 5.5.0

# python 2.x (via pyenv)
brew install pyenv pyenv-virtualenv
pyenv install 2.7.11
pyenv rehash
pyenv global 2.7.11

# ruby (via rvm)
# TODO: ...
```
