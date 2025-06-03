pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/Manhcuong05/DemoCI.git'
            }
        }

        stage('Build Java') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run Program') {
            steps {
                bat 'java HelloWorld'
            }
        }
    }
}
