pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Etapa Build no disponible'
            }
        }
        stage('Test') {
            steps {
                echo 'Etapa Test no disponible'
            }
        }
        stage('Deploy') {
            steps {
                sh 'docker-compose down'
                sh 'docker-compose rm 745074b99085ed28df67db347271ffb45427f45fdc9ab410161fa73be1c5d831'
                sh 'docker-compose up -d --build'
            }
        }
    }
}