pipeline {
    agent any
    stages {
        stage('checkout code') {
            steps {
                git 'https://github.com/Hemanth42004/Apache_httpd-server-deployment-using-Ansible-and-Jenkins'
            }
        } 
        stage('Playbook is running') {
            steps {
                sh'ansible-playbook -i inventory.ini Apache_playbook.yml'
            }
        }
    }
}


