pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Chandumaharshi10/MiniFlipkart.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
