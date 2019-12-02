pipeline {
    agent any
    stages {
        stage ('Gradle build') {
            steps {
                echo 'Running graddle build'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: ''dist/tranSchedule.zip
            }
        }
    }
}
