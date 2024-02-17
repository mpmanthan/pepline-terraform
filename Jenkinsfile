pipeline {
    agent any

    stages {
        stage('init') {
            steps {
                terraform init
            }
        }
        stage('fmt') {
            steps {
                terraform fmt
            }
        }
        stage('plan') {
            steps {
                terraform plan
            }
        }
    }
}
