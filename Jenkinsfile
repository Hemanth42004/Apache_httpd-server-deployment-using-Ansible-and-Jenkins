pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Hemanth42004/Apache_httpd-server-deployment-using-Ansible-and-Jenkins'
            }
        }
        stage('Run Ansible Playbook') {
            steps {
                sh 'ansible-playbook -i inventory.ini Apache_playbook.yml'
            }
        }
    }
    post {
        success {
            echo 'Deployment Successful 🚀 Apache is running'
        }
        failure {
            echo 'Deployment Failed ❌ Check logs'
        }
    }
}
