Installation of jenkins with a AWS Stack or jenkins playbook

1- Installation with Stack
- Load the jenkins_VM.yml  stack using the AWS training cloud service
- connect to a browser: http://@ip:8080/

- connect to jenkins-dashboard: username= admin password= admin

2- Installation with jenkins playbook

- git clone https://github.com/franck-art/stack-jenkins.git

- cd stack-jenkins

- ansible-galaxy role install -r requirements.yml

- ansible-playbook install_jenkins.yml

- connect to a browser: http://@ip:8080/

- connect to jenkins-dashboard: username= admin password= admin
