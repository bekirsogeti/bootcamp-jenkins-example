#!groovy

pipeline{

    agent any

    stages{
       stage('CompileJob') {
          build 'Compile Job'
       }
       stage('Test') {
          build 'Test'
       }
       stage('Deploy') {
          build 'Deploy'
       }
    }
}
