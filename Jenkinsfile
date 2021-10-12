pipeline {
    agent any
    stages {
        stage('Compile and Clean') {
            steps {
            sh "mvn clean compile"
            }
        }


        stage('deploy') {
            steps {
                sh "mvn package"
            }
        }
    }
}
