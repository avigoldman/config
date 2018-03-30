# Config

This is my configuration. It's all my dotfiles, along with a simple script to set up my environment and install programs I can't live without.

Built by following this [wonderful tutorial](https://developer.atlassian.com/blog/2016/02/best-way-to-store-dotfiles-git-bare-repo/).

## Downloading

The bootstrap script will download clone this repo, stash the differences in the local and remote dotfiles, and load 'em in.

```sh
bash <(curl -s  https://raw.githubusercontent.com/avigoldman/config/master/bin/bootstrap)
```

## Using and modifying the config

This bring along a `config` alias for commiting in changes into the config repository.


For example if you update your `.zshrc` file you can push up the changes like so.

```sh
config add .zshrc
config commit -m "Updated zshrc"
config push
```

## Installing the programs and env

After downloading this repo, run `./bin/install` to install the following:
* Homebrew
* Cask
* Google Chrome
* iterm2
* VS Code
* spotify
* Slack
* Muzzle
* Alfred
* Tor Browser
* Postman
* mamp
* Postico
* Sequel Pro
* Mongodb Compass
* postgresql
* mongodb
* Oh My Zsh
* n
* trash-cli
* spoof
