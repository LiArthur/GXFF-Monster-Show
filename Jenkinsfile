pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'git clone https://github.com/LiArthur/GXFF-Monster-Show.git'
                sh 'cd web'
                echo 'building web image'
                sh 'docker build -t caozz0828/monster:web .'
                echo 'echo successfully build web image'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
