############## Playbook d'installation de jenkins via un playbook Ansible ######
# Installer Ansible ou utliser la stack ansible

1-charger la Stack Ansible grace au service Cloud formation de AWS 

2- se connecter via Mobaxterm

# Installer Jenkins

1- git clone 

2- cd install-jenkins_via_ansible

3- ansible-galaxy role install -r requirements.yml

4- ansible-playbook install_jenkins.yml 
