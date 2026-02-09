pipeline {
    agent any

    stages {
        stage("Build dotnet project") {
            steps {
                bat "dotnet build"
            }
        }

        stage("Test dotnet project") {
            steps {
                bat "dotnet test"
            }
        }
    }
}
