############## Playbook d'installation de jenkins via un playbook Ansible ######
# Prerequis: Installer Ansible ou utliser la stack ansible

Dans mon cas, j'utilise la stack ansible

1-charger la Stack Ansible grace au service Cloud formation de AWS 

2- se connecter via Mobaxterm

# Installer Jenkins

1- git clone https://github.com/franck-art/install-jenkins_via_ansible.git

2- cd install-jenkins_via_ansible

3- ansible-galaxy role install -r requirements.yml

4- ansible-playbook install_jenkins.yml 

5- Ouvrir le port 8080 (via le security-goup sur AWS)

6- se connecter sur un navigateur: http://@ip:8080/
