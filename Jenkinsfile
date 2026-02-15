pipeline {
    agent {
        docker {
            image 'node:18'
            args '-u root'
        }
    }

    stages {
        stage('Instalar dependencias') {
            steps {
                sh 'npm install'
            }
        }

        stage('Build OK') {
            steps {
                sh 'echo Pipeline funcionando 🚀'
            }
        }
    }
}
