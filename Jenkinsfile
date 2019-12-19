pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh './gradlew build'
                archiveArtifacts artifacts: 'dst/trainSchedule.zip'
            }
        }
    }
}
