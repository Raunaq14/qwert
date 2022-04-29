pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo 'build running'
                bat 'python sniffle.py'
            }
        }
    }
}
