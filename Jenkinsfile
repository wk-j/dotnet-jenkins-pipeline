pipeline {
    agent { dockerfile true }
    stages {
        stage ("Test") {
            steps {
                sh 'dotnet build src/MyApp/MyApp.csproj'
                sh 'dotnet publish src/MyApp/MyApp.csproj'
            }
        }
    }
}