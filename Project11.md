# Project 11 ANSIBLE


### Update and Install ansible
* sudo apt update
* sudo apt install ansible
![installation image](images/image1.png)
### Configuration for Ansible on Jenkins Server
* Configure Ansible on Jenkins Server
![Configure Ansible image](images/image2.png)


### Testing the Ansible Configuration
* Test using "ls ls /var/lib/jenkins/jobs/ansible/builds/<build_number>/archive/"
![testimage](images/image3.png)


### Preparing your development environment using Visual Studio Code
* Clone git to local development area "git clone < repository link >"
![git clone repo](images/image4.png)

### Preparing your development environment using Visual Studio Code
* Clone git to local development area "git clone < repository link >"
![git clone repo](images/image4.png)
* Branch created "prj-11" - git checkout -b prj-11
* create new directories "Playbooks & Inventory" -
![setup for dev complete image](images/image5.png)

### Preparing your development environment using Visual Studio Code
* Clone git to local development area "git clone < repository link >"
![git clone repo](images/image4.png)
* Branch created "prj-11" - git checkout -b prj-11
* create new directories "Playbooks & Inventory" -
![setup for dev complete image](images/image5.png)
* Dev.yml - "Setup for Dev"
![setup for dev.yml image](images/image6.png)

## Ansible Test
* Ansible Complete - "ansible-playbook -i inventory/dev.yml playbooks/common.yml"
![Ansible Project Completed](images/image7.png)
