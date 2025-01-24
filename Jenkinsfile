pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Run Echo Command') {
            steps {
                sh 'chmod +x ./script.sh'
                sh './script.sh'
            }
        }
    }
}
