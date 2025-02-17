pipeline {
    agent any
     stages {
        stage('Restore dependencies') {
            steps {
                bat 'dotnet restore'
            }
        }
        stage('Build app') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Test app') {
            steps {
                bat 'dotnet test'
            }
        }
    }
}