pipeline {

    agent any

    stages {

        stage('Build') {
            steps {
                bat 'gradle build'
            }
        }

        stage('Run') {
            steps {
                bat 'gradle run'
            }
        }

    }
}
