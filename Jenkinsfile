pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sudo docker help
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
