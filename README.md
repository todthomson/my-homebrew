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


# ruby v.x
brew install openssl rbenv


# python 2.x
brew install pyenv pyenv-virtualenv
pyenv install 2.7.11
pyenv rehash
pyenv global 2.7.11
```
