pipeline {
    agent any

    tools {
        gradle 8.10.2
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
