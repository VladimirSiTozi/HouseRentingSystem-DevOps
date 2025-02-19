pipeline {
    agent { label 'windows' }
    tools {
        msbuild 'MSBuild 2022'
    }
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