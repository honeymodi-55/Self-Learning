pipeline {
    agent any
    stages {
        stage ('Compiling Java') {
            steps { sh 'javac java-code1.java'}
        }
        stage ('Executing Java File') {
            steps {sh 'java FibonacciExample1'}
        }    
    }
}