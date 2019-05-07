pipeline {
    agent any

    stages {
        stage('build job: '1. Compile', quietPeriod: 1') {
            steps {
                echo 'Building Code..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing The App..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the App....'
            }
        }
    }
}
