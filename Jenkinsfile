pipeline {
    agent { label 'master' } 
    parameters{
        string(name: 'AppName', defaultValue: '', description: '')
    }

    stages {
            
        stage('Build') {
            steps {
                echo "Building our application"
                sh '''pwd
                    ls'''
            }
        }
        
        stage('Unit Test') {
            steps {
                echo 'Running unit test cases'
            }
        }
        
        stage('Deploy - Dev') {
            steps {
                echo 'Deploying to dev environment'
            }
        }

        stage('Deploy - Test') {
            steps {
                echo 'Deploying to test environment'
            }
        }

        stage('Deploy - Prod') {
            steps {
                echo 'Deploying to prod environment'
            }
        }
    }
}
