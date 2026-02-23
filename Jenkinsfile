pipeline {
    agent any
    tools {
        nodejs 'NodeJS'  // must match the name you gave it in Tools
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}