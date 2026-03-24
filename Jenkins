pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat 'javac Demo.java'
            }
        }
        stage('Run') {
            steps {
                bat 'java Demo'
            }
        }
    }
}
