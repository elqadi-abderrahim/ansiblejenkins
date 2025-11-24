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
                sh 'ansible-playbook playbook.yml'
            }
        }
    }
}
