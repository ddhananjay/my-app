pipeline {
    agent any

    stages {
        stage("build") {
            steps {
                echo 'Building application'
                sh 'gradle clean build'
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
