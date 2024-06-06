pipeline {
    agent any
    
    stages {
        stage('CONFIGURE APPLICATION SOURCE CODE') {
            steps {
                sh 'dotnet build .sln'
            }
        }
    }
}
