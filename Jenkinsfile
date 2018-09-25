pipeline {
    agent { dockerfile true }
    stages {
        stage ("Test") {
            steps {
                sh 'dotnet build src/MyApp/MyApp.csproj'
            }
        }
    }
}