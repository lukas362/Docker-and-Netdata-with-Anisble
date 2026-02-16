# Launch Docker with Ansible and monitor your system with Netdata
This simple playbook allows you to launch Docker with the help of Anisble and use Netdata to monitor you system hardware and usage 

## Requirements
- Linux with systemd
- Ansible installed + Ansible docker community (ansible-galaxy collection install community.docker) 
- Docker installed
- Sudo privileges
- Python + Python library (pip install docker) 

## How to use and stop this playbook: 
1. How to run - ansible-playbook docker.yml -K (-K = Ansible asks for your sudo password to run this playbook. Needed because Docker needs root access) 
2. How to stop - sudo systemctl stop docker
3. Access Netdata monitor: http://localhost:19999 

## Useful docker commands: 
- docker ps = List running containers
- docker images = List downloaded images
- docker run = Run a container

## Useful Netdata commands:
- docker stop netdata = stops Netdata
- docker logs -f netdata = shows realtime logs of your system
