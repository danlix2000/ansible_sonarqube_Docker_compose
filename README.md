# Ansible playbook for setup Sonarqube server uisng docker compose in Ubuntu 18.04 LTS

In ansible.cfg file changed inventory location to current dicrectory

inventory       = hosts

- Docker compose file saved inside sonarfile folder 

Run playbook 

```
ansible-playbook sonar-docker.yml

```

Here I have used private IP to connect with sonar server 