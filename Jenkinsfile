pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('pandas') {
            steps {
                sh 'python3 pandas.py'
            }
        }
    }
}
