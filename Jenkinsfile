pipeline {
    agent any

    stages {
        stage('Build / Test / Deploy') {
            steps {
                echo 'Gotta Go Fast..'
					 echo 'BUILD_TAG: ${BUILD_TAG}'
                sh 'mvn clean deploy'
            }
        }
    }
}
