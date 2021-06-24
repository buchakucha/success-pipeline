pipeline {
  agent any
  tools {nodejs "nodejs"}
  options { timestamps () }
  stages {
        stage('Build') {
            steps {
                echo 'Building..'
		        sh "node hello.js"
            }
        }
        stage('Test') {
             steps {
                echo 'Testing..'
		        sh "node hello.js"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
} 
