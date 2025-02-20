pipeline {
    agent any  // Runs on any available agent

    stages {
        stage('Generate Documentation') {
            steps {
                script {
                    gradleTasks('generateDocs')  // Runs the Gradle task directly
                }
            }
        }
    }
}
