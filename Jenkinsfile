pipeline {
    agent any

    stages {
        stage('Clonar código') {
            steps {
                echo 'Clonando repositorio...'
            }
        }

        stage('Instalar dependencias') {
            steps {
                sh 'npm install'
            }
        }

        stage('Ejecutar aplicación') {
            steps {
                sh 'echo Aplicación lista 🚀'
            }
        }
    }
}
