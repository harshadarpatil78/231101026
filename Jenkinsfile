pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/harshadarpatil78/231101026.git'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean install'   // use "sh mvn clean install" if Linux
            }
        }
    }
}
