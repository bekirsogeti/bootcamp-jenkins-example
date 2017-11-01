#!groovy

pipeline{

    agent any

    stages{
       stage('CompileJob') {
           step {
            build 'Compile Job'
           }
       }
       stage('Test') {
           step {
            build 'Test'
           }
       }
       stage('Deploy') {
           step {
            build 'Deploy'
           }
       }
    }
}
