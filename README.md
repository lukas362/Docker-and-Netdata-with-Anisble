# Launch Docker with Ansible
This simple playbook allows for you to launch Docker with the help off Anisble

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
