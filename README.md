# Dotfiles
### My personal dot files for linux systems

## Install
Install git, fortune, and cowsay
```bash
sudo apt install git fortune cowsay
```

Download and install dotfiles to home directory
```bash
cd ~
git init
git remote add origin https://github.com/AndersBallegaard/dotfiles.git
git reset --hard origin/master
git branch --set-upstream-to=origin/master master
git pull
source ~/.bashrc
```

## Update
The files are automaticly updated every 10 startups.
If you want to manually update type the following
```bash
update-dotfiles
```
