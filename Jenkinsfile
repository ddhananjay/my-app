pipeline {
    agent any

    tools {
        gradle 'Gradle-8.2'
    }

    stages {
        stage("build") {
            steps {
                echo 'Building application'
                sh './gradlew clean build'
            }
        }
        stage("test") {
            steps {
                echo 'testing application'
            }
        }

        stage("deploy") {
            steps {
                echo 'deploying application'
            }
        }
    }

}
