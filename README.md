dotfiles
========

My personal setup

From: http://net.tutsplus.com/tutorials/tools-and-tips/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles/

Run in the following order:

- bash install-deps.sh (homebrew, rvm, etc)
- Put anything you want to keep from .bash_profile into ~/.extras
- bash bootstrap.sh (copies dotfiles to ~)
- cd ~/
- bash .brew (installs CLI stuff)
- bash .cask (installs common apps)
