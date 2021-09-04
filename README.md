# Automation Network

This repo is a an example of how to run command in cisco devices and save the results in a file using Ansible 


### Prerequisites
-Linux Machine
- Python 2/3
- Ansible v>=2.10 

### Local setup

1. `git clone https://github.com/MetraneAbdelmounim/Automation-Network.git`
2. `cd Automation-Network`
3. `cat "hosts.sample" >  "hosts"`
4. make some change in the hosts file
5. run `ansible-playbook show-command.yml`
6. show the results in the show-output directory
