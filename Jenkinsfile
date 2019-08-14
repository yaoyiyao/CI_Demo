pipeline {
    agent any

    stages {
        stage('Checkout') {
          checkout scm git@github.com:yaoyiyao/CI_Demo.git
        }

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
}
