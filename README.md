# Launch Docker with Ansible
This simple playbook allows for you to launch Docker with the help off Anisble

<img width="1537" height="319" alt="Skärmbild 2026-02-15 190909" src="https://github.com/user-attachments/assets/c923064b-16d8-43c6-9610-cdd57e2ce8d3" />

## Requirements
- Linux with systemd
- Ansible installed
- Docker installed
- Sudo privileges

## How to use and stop this playbook: 
1. How to run - ansible-playbook docker.yml -K
2. How to stop - sudo systemctl stop docker

## Useful docker commands: 
- docker ps = List running containers
- docker images = List downloaded images
- docker run = Run a container
