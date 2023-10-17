On source: 

sudo apt update && sudo apt upgrade -y
sudo apt install ansible -y
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
az login
ansible-playbook main.yml
