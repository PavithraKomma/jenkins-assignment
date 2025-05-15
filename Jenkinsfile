pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/pavithrakomma/jenkins-assignment.git'
            }
        }
        stage('Run Python') {
            steps {
                sh 'python3 script.py'
            }
        }
    }
}

