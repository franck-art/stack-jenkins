############## Playbook d'installation de jenkins via un playbook Ansible ######
# Prerequis: Installer Ansible ou utliser la stack ansible

NB: Si vous avez ansible installé et que vous etes directement connecté sur votre machine, passez à l'étape (Installer Jenkins).

Dans mon cas, j'utilise la stack ansible

1-charger la Stack Ansible grace au service Cloud formation de AWS 

2- se connecter via Mobaxterm ou putty (pour une connexion à distance)


# Installer Jenkins

1- git clone https://github.com/franck-art/install-jenkins_via_ansible.git

2- cd install-jenkins_via_ansible

3- ansible-galaxy role install -r requirements.yml

4- ansible-playbook install_jenkins.yml 

5- Ouvrir le port 8080 (via le security-goup sur AWS)

6- se connecter sur un navigateur: http://@ip:8080/
