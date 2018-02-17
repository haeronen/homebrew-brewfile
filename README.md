# Custom brewfile for Homebrew Bundle
Brewfiles to automate global OSX app & utiltity installation.

## Requirements
Have [Homebrew](https://github.com/Homebrew/brew) for installing the Apps & dependencies.


## Usage

#### Clone the repo
    $ git clone https://github.com/haeronen/homebrew-brewfile.git $HOME/.homebrew-brewfile


#### Link Brewfile as global one:
    $ ln -s $HOME/.homebrew-brewfile/<file kind>/Brewfile $HOME/.Brewfile


#### Install dependencies from global Brewfile:
    $ brew bundle install --global
