pipeline {
    agent any
    tools {
        maven 'Maven 3.5.0'
        ant 'Ant 1.8.0'
        jdk 'jdk8'
    }
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                '''
            }
        }
       stage('Build') {
            steps {
                echo "Build"
            }
        }
        stage('Test') {
            steps {
                echo "Test"
            }
        }
        stage('Deliver') { 
            steps {
                echo "Deliver"
            }
        }
        stage('Deliver-to-DEV') {
            steps {
                echo "Deliver-to-DEV"
            }
        }
        stage('Deliver-to-QA') {
            steps {
                echo "Deliver-to-QA"
            }
        }
        stage('Deliver-to-Prod') {
            steps {
                echo "Deliver-to-Prod"
            }
        }
    }
}
  
