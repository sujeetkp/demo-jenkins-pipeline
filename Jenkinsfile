pipeline {
    agent {
        label 'linux'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh '''
                hostname
                date
                ls -lrt
                '''
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
