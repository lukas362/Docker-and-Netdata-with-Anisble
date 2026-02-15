# Launch Docker with Ansible
This simple playbook allows for you to launch Docker with the help off Anisble

<img width="540" height="315" alt="Skärmbild 2026-02-15 190958" src="https://github.com/user-attachments/assets/ae7e6da1-164b-4f9e-92be-4431c9eb843c" />

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
