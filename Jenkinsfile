pipeline {
    agent any

    tools {
        gradle 
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
