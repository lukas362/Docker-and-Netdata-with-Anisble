# Launch Docker with Ansible and monitor your system with Netdata
This simple playbook allows you to launch Docker with the help of Anisble and use Netdata to monitor you system hardware and usage 

## Requirements
- Linux with systemd
- Ansible installed + Ansible docker community (ansible-galaxy collection install community.docker) 
- Docker installed
- Sudo privileges
- Python + Python library (pip install docker) 

## How to use and stop this playbook: 
```bash
1. How to run - ansible-playbook docker.yml -K (-K = Ansible asks for your sudo password to run this playbook.
Needed because Docker needs root access)
```

```bash
2. How to stop - sudo systemctl stop docker
```

```bash
3. Access Netdata monitor: http://localhost:19999
```

## Useful docker commands: 
```bash
- docker ps = List running containers
```

```bash
- docker images = List downloaded images
```

```bash
- docker run = Run a container
```

## Useful Netdata commands:
```bash
- docker stop netdata = stops Netdata
```

```bash
- docker logs -f netdata = shows realtime system usage of your system (might need to do ctrl + c, if it doesn't stop)
```
