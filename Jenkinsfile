pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                cd web
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
