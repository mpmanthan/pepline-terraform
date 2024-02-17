pipeline {
    agent any

    stages {
        stage('init') {
            steps {
                sh terraform init
            }
        }
        stage('fmt') {
            steps {
                sh terraform fmt
            }
        }
        stage('plan') {
            steps {
                sh terraform plan
            }
        }
    }
}
