pipeline {
    agent any

    tools {
        gradle "Gradle 8.10.2"
    }

    stages {
        stage("build") {
            steps {
                echo "Java VERSION"
                sh 'java --version'
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
