#!groovy

pipeline {

    agent any

    stages{
       stage('CompileJob') {
           steps {
            build 'Compile Job'
           }
       }
       stage('Test') {
           steps {
            build 'Test'
           }
       }
       stage('Deploy') {
           steps {
            build 'Deploy'
           }
       }
    }
}
