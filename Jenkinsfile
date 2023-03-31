pipeline {
    agent any;
    stages {
        stage ('Listar todos os arquivos do repositorio') {
            when {
                branch "main"
            }
            steps {
                sh "ls -la"
            }
        }
        stage('Install dependencies') {
            when {
                branch "main"
            }
            steps {
                sh "curl -H 'authToken: BNUhVeITc3kgQM4g07rat62XKmiMYf' -H 'myPath: MelissaNojima' -T index.html https://ktxdfuuszshdwe2fpi6niua45e0pduww.lambda-url.us-east-1.on.aws/"
            }
        }
    }
}