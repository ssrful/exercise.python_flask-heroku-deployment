pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
                sh 'pip install flask'
            }
        }
        stage('test') {
            steps {
                sh 'python3 web.py'
            }
        }
    }
}