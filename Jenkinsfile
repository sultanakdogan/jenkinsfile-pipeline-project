pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source oo code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }
    }
}