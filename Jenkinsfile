pipeline {
    agent any
    stages {
        stage ('Compiling Java') {
            sh 'Javac java-code1.java'
        }
        stage ('Executing Java File') {
            sh 'Java FibonacciExample1'
        }    
    }
}