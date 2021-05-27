pipeline {
    agent any
    stages {
        stage ('Compiling Java') {
            steps { sh 'Javac java-code1.java'}
        }
        stage ('Executing Java File') {
            steps {sh 'Java FibonacciExample1'}
        }    
    }
}