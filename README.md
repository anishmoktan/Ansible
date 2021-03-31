# Ansible

## How to Create a Basic Ansible Playbook on AWS

1. Spin up two EC2 Instances: 
    - Instance A for Pilot Node
    - Instance B for Control Node
    * For this tutorial, open port 22 for all traffic in the security group
2. SSH into both instances using your terminal
3. On your Pilot Node, change into .ssh directory by using the command ``` cd .ssh ```