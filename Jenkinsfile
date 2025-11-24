pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Exécuter le playbook Ansible') {
            steps {
                bat 'ansible-playbook playbook.yml'
            }
        }
    }
}
