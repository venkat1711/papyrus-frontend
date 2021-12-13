pipeline {
    agent any
	stages {
        stage('Git Checkout') {
            steps {
                git credentialsId: 'd327c63d-3d2f-4b7c-9046-0008d1c1d0eb', url: 'https://github.com/venkat1711/papyrus-frontend.git'
		
            }
        }
	
    stages {
        stage('build') {
            steps {
                sh 'npm install'
		
            }
        }
	stage('run') {
            steps {
                sh 'npm start'
		
            }
        }
    }
}
