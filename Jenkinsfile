pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                script {
                    if (isUnix()) {
                        sh 'python3 hello.py'
                    } else {
                        bat 'python hello.py'
                    }
                }
            }
        }
    }
}