pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/kuruvaindrajith/Jenkins.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
