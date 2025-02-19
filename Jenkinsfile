pipeline {
    agent any 
    stages {
        stage('Build Project') {
            steps {
                sh 'dotnet build'
            }
        }
        stage('Run dotnet tests') {
            steps {
                sh 'dotnet test'
            }
        }
    }
}
