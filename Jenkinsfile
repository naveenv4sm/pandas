pipeline {
    agent any

    tools {
        python 'python3'
    }

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

