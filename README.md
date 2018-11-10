# One-click-to-deploy-swarm-by-ansible
cp -r * /etc/ansible/roles/


yml
- name: "Provision Docker Swarm Cluster"

  hosts: all

  roles:
    - { role: platform.docker_swarm }
