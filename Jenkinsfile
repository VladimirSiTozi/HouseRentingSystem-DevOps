pipeline {
    agent { label 'windows' } // Ensure this label matches a Windows node
    stages {
        stage('Build Project') {
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
