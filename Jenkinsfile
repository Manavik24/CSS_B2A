pipeline {
    agent any

    stages {
        stage('Generate Documentation') {
            steps {
                script {
                    //sh './gradlew generateDocs'  // For Linux/macOS
                    bat 'gradlew.bat generateDocs'  // For Windows
                }
            }
        }
    }
}
