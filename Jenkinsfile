pipeline {
    agent any

    stages {
        stage('Clonar') {
            steps {
                git 'https://github.com/gianLM23/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Construyendo aplicación...'
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutando pruebas...'
            }
        }

        stage('Run App') {
            steps {
                bat 'python app.py'
            }
        }
    }
}