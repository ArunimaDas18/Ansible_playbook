# Ansible_playbook
This is repo contains 3 playbooks and an inventory file , which are used to create new file, create_user and install docker 

## Step 1:  
Create a ec2 instance give name ansible_master and create a key pair ansi_key -> create 3 other similar instance  with same key pair and name then ansible_server1,ansible_server2,ansible_server3 respectively .

## Step 2: Connect anisble_master to instance and install ansible 

```bash
sudo apt update  
sudo apt install ansible
```

## Step 3 : Connect the master server to the slave servers with the help of SSH
