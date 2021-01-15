pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Only'
                sh 'mvn -DskipTests clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Tests Only'
                sh 'mvn test'
            }
        }
    }
}
