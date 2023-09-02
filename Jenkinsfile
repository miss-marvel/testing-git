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

    }
}
