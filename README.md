# ansible
Learning Ansible

1) Install git (latest version)
2) git clone https://github.com/git/git
3) Configure git to clone from this repository with the following command:
  git clone https://github.com/prenalds/ansible.git
  install python dev tools with command: sudo apt-get python-pip python-dev
NOTE: You will be prompted for your username/password
3) Install ansible (latest version): first: sudo apt-get install software-properties-commom second: sudo apt-add-repository ppa:ansible/ansible  third: sudo apt-get install ansible
4) Change current directory to "ansible" : cd ansible
5) To run this playbook:  ansible-playbook site.yml -i inventory/local.yml

