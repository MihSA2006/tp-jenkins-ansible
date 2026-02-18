pipeline {
    agent any

    stages {
        stage('Run Ansible Playbook') {
            steps {
                sh 'ansible-playbook playbook.yml'
            }
        }
    }
}

