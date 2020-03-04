pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'mvn clean build -DskipTests=true'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
					 sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
					 sh 'mvn deploy'
            }
        }
    }
}
