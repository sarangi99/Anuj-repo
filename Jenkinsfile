pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/sarangi99/Anuj-repo.git'

            }
        }

stages {
        stage('Compile') {
            steps {
                sh 'mvn clean compile'
            }
        }
    }
}
