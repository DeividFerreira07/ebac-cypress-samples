
//Para projeto Web

pipeline {
    agent any

    stages {
        stage('Instalar dependencias') {
            steps {
                sh 'npm ci || npm install'
            }
        }

        stage('Executar Testes Web (Cypress)') {
            steps {
                sh 'NO_COLOR=1 npm run cy:run'
            }
        }
    }
}








//Para projeto API


pipeline {
    agent any

    stages {
        stage('Instalar dependencias') {
            steps {
                sh 'npm ci || npm install'
            }
        }

        stage('Executar Testes API') {
            steps {
                sh 'npm test'
            }
        }
    }
}
