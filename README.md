# Ansible Docker Seed

This is a jumping off point for developing Ansible provisioning and testing against Docker containers.

## Setup
### Install Galaxy Roles

    $ ansible-galaxy install -r requirements.yml -p galaxy_roles

### Start Docker Containers

    $ docker-compose up -d

## Deploy 
### Locally

    $ ansible-playbook -i environments/docker site.yml

## Cleanup
### Stop Docker Containers

    $ docker-compose down

    