# *NIX Fresh Installation

> Essential tools and apps you are too lazy to install

Don't like to recovering your sysmtem from a backup? With this tool you can install a fresh copy of *macOS* or *debian based linux* any day and still have all the tools you want.


## Requirements

Not much, just a modern version of mac/linux with an internet connection and `bash` will work.

## Use

To get specific tools/apps, just fork this repo to fit your needs.

### Easy install:

```shell
bash -c "$(curl -fsSL https://raw.githubusercontent.com/pablopunk/fresh-install/master/fresh-install.sh)"
```


## What does this install?

| | Mac | Linux (debian) |
|-|:---:|:-----:|
|[homebrew](https://brew.sh)|x||
|[homebrew cask](https://caskroom.github.io)|x||
|[some cli tools from brew](./install/brew)|x||
|[some cli tools from apt](./install/apt)||x|
|[some cli tools from pip3](./install/pip3)|x|x|
|[some npm modules](./install/npm)|x|x|
|[some apps](./install/cask)|x||
|[my dotfiles](https://github.com/pablopunk/dotfiles)|x|x|
|keyboard config|x||
|mouse config|x||
|global git config|x|x|
|[Disable Apple persistance](https://apple.stackexchange.com/questions/124367/stop-mavericks-from-relaunching-applications)|x||
