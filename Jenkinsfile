// Jenkinsfile (Declarative Pipeline)

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
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
    
    post {
        always {
            echo "Jenkins Success"
        }
        failure {
            echo "Jenkins Failed, please check again!"
        }
    }
}
