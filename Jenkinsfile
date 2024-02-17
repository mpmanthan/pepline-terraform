pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // this git repo 
                checkout scm 
         }
        }
        stage('Terraform init') {
            steps {
                sh 'terraform init'
            }
        }
        stage('Terraform apply') {
            steps {
                sh 'terraform destory --auto-approve'
            }
        }
        
    }
}
