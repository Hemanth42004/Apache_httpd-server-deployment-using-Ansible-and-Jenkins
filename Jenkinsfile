pipeline {
    agent any
    stages {
        stage('checkout code') {
            steps {
                git ''
            }
        } 
        stage('Playbook is running') {
            steps {
                sh'ansible-playbook -i inventory.ini Apache_playbook.yml'
            }
        }
    }
}


