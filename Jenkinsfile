
//Para projeto Web

pipeline {
    agent any

    stages {
        stage('Instalar dependencias') {
            steps {
                bat 'npm ci || npm install'
            }
        }

        stage('Executar Testes Web (Cypress)') {
    steps {
        bat 'npx cypress run'
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
                bat 'npm ci || npm install'
            }
        }

        stage('Executar Testes API') {
            steps {
                bat 'npm test'
            }
        }
    }
}
