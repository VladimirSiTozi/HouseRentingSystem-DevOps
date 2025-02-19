pipeline {
    agent {
        dockerContainer {
            image 'mcr.microsoft.com/dotnet/sdk:6.0'
        }
    }
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
