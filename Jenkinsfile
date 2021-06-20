pipeline {
    agent any
  options { timestamps () }
  stages {
        stage('Build') {
            steps {
                echo 'Building..'
		sh "ruby hello.rb"
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