pipeline {
    agent any

    stages {
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