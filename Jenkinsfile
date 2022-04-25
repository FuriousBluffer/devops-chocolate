pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo 'running build'
                bat 'python sniffle.py'
            }
        }
    }
}
