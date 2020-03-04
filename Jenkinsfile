pipeline {
    agent any

    stages {
        stage('Build / Test / Deploy') {
            steps {
                echo 'Gotta Go Fast..'
                sh 'mvn clean deploy'
            }
        }
    }
}
