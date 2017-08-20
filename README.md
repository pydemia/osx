# Mac OS X
This contains the contents of MAC OS X.

# Setup


## Installation

### xcode and `Homebrew`
```sh
xcode-select --install
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"


==> The following new directories will be created:
...
Press RETURN to continue or any other key to abort
==> /usr/bin/sudo /bin/mkdir -p /usr/local/Cellar /usr/local/Homebrew /usr/local/Frameworks /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/opt /usr/local/sbin /usr/local/share /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var
Password:

brew install caskroom/cask/brew-cask

```
### zsh & oh-my-zsh

```sh
brew install zsh
curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh
```

## iTerm2

Theme : Argonaut, Brogrammer, Cobalt2, Glacier, ..


## R
brew install r
defaults write org.R-project.R force.LANG en_US.UTF-8


## `Fn` keys as Standard

`System Preferences` > `Keyboard` > `Keyboard` > Check `Use F1, F2, etc. keys as standard function keys`  


