pipeline {
    agent any
    stages {
        stage('Checkout Repo') {
            steps {
                git 'https://github.com/mohamed255255/Cloud-Task.git'
            }
        }
        stage('Run Script') {
            steps {
                bat 'CloudTask.bat'
            }
        }
    }
}
