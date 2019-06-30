pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git clone https://github.com/LiArthur/GXFF-Monster-Show.git
                echo "building web docker image"
                cd web
                docker login -u caozz0828 -p Aws@12345
                docker build -t caozz0828/monster:webv2
                echo "building app docker image"
                docker build -t caozz0828/monster:appv2
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