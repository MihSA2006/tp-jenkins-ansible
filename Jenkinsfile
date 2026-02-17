pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/MihSA2006/tp-jenkins-ansible.git'
            }
        }

        stage('Run Ansible Playbook') {
            steps {
                sh 'ansible-playbook playbook.yml'
            }
        }
    }
}
