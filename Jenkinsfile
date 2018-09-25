pipeline {
    agent { dockerfile true }
    states {
        state("Test") {
            steps {
                sh 'dotnet build src/MyApp/MyApp.csproj'
            }
        }
    }
}