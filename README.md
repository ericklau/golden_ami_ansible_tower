# The Golden AMI Repo

Golden AMI Repo is used for the creation of an EC2 that is stood up and configured w/ special COTS, security scanning, dependencies for re-usability and portabilities of VM's.  

## Prerequisite
1. Ansible Tower
2. Ansible node w/ enough credentials to launch an EC2 enable EBS encryption
3. All Networking to flow through ansible node to newly created EC2

## Usage

```bash
ansible-playbook site.yml -i hosts
```
