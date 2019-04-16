# Dotfiles
### My personal dot files for linux systems

## Install
Install Dependencys
```bash
#Needed
sudo apt install git fortune cowsay

#Recommended
sudo apt install screen nano
```

Download and install dotfiles to home directory
```bash
cd ~
# Don't use git clone, git will get angry
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
