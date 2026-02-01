pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build and Test') {
            steps {
                bat '''
                cd C:\\Users\\PRANAV\\CILabProject
                "C:\\Program Files\\Apache\\apache-maven-3.9.12\\bin\\mvn.cmd" test
                '''
            }
        }
    }
}
