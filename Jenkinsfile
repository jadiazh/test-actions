pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'ls -la'
                sh 'pwd'
                
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh 'printenv|sort'
            }
        }
    }
}
