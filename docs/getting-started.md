# Getting started

## Install requirements

### Docker

Run:
```
curl -sSL https://get.docker.com | sh
sudo usermod -aG docker $(whoami)
```

### Git

Run: `sudo apt install git -y`


## Install utilities

`sudo apt install micro batcat`


## Set aliases

Edit/create alias file with: `micro ~/.bash_aliases`
Add the folowing:
```
alias bat='batcat'
alias ll='ls -lahv --color-auto --group-directories-first'
```


## Set hostname
Run `micro /etc/hostname` 


