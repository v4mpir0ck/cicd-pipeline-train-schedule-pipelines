pipeline {
    agent nodejs
    stages {
        stage('Gradle build') {
            steps {
            sh ./gradlew build --no-daemon
            }
        }

}
