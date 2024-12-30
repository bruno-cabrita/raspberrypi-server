# Getting started

## Set static IP

[Instructions](https://www.jeffgeerling.com/blog/2024/set-static-ip-address-nmtui-on-raspberry-pi-os-12-bookworm)


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
```bash
alias bat='batcat'
alias ll='ls -lahv --color-auto --group-directories-first'
```


## Set hostname
Run `micro /etc/hostname`
Run `micro /etc/hosts`
Verify: `hostname -f`
