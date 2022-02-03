pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Hello build'
                bat 'mvn package'
            }
        }
        stage('test') {
            steps {
                echo 'Hello test'
                bat 'mvn test -DmuleTest'
            }
        }
        stage('deploy') {
            steps {
                echo 'Hello deploy'
                //bat 'mvn package'
            }
        }

    }
}