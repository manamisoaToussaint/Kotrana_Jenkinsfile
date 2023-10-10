pipeline {
    agent any

    stages {
        stage('init') {
            steps {
                echo "Hi, this is Toussaint"
                echo "hano tay!!"
            }
        }

        stage('Build') {
            steps {
                echo "Starting build with maven"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying in staging Area"
            }
        }

        stage('TAY') {
            steps {
                echo "Deploying TAY in PROD"
            }
        }
    }
}