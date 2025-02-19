pipeline {
    agent any 
    stages {
        stage('Build Projetc') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Run dotnet tests') {
            steps {
                bat 'dotnet test'
            }
        }
    }
}