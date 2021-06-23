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
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}