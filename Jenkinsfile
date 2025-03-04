pipeline {
    agent any
    stages {
        stage('Version Check') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Run Pandas Script') {
            steps {
                sh 'python3 pandas.py'
            }
        }
    }
}

