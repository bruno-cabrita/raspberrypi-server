# Raspberry Pi Server

This is a personal guide to setup a home server using a Raspberry Pi runnig services with docker.

### Requirements

The server must have SSH enabled and Docker + Git installed.

### Instructions

- [Getting started](docs/getting-started.md)


## Commands

| Command                               | Description                              |
|:------------------------------------- |:---------------------------------------- |
| `sudo reboot`                         | Reboot server                            |
| `docker ps -a`                        | List all containers                      |
| `nmcli device status`                 | List network devices                     |
| `nmcli device show <device>`          | Show network device (e.g: eth0) details  |
| `sudo nmtui edit "<connection_name>"` | Edit network settings (ip, gateway, etc) |
