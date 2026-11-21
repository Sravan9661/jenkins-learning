pipeline{
    agent any
    stages{
        stage('Checkout'){
            steps {
                sh 'echo here we pull code from git into jenkins workspace'
            }
        }
        stage('install'){
            steps {
                sh 'echo here we install all the dependecies required for package'
            }
        }
        stage('Test'){
            steps {
                sh 'echo here code will be tested'
            }
        }
        stage('Build Image'){
            steps {
                sh 'echo here image will be built with docker'
            }
        }
        tage('Deploy'){
            steps {
                sh 'echo here we push image into ecr and update in git for argoCD to pickup the code to deploy'
            }
        }

    }
}