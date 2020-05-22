############## Jenkins installation playbook using an Ansible playbook ######
# Prerequisites: Install Ansible or use the ansible stack

NB: If you have ansible installed and you are directly connected to your machine, go to step (Install Jenkins).

In my case, I use the ansible stack

1-load the Ansible Stack thanks to AWS Cloud training service 

2- connect via Mobaxterm or putty (for a remote connection)


# Install Jenkins

1- git clone https://github.com/franck-art/install-jenkins_via_ansible.git

2- cd install-jenkins_via_ansible

3- ansible-galaxy role install -r requirements.yml

4- ansible-playbook install_jenkins.yml 

5- se connecter sur un navigateur: http://@ip:80/
