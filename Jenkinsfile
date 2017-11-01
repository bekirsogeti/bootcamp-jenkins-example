#!groovy

pipeline{

    agent any

    stages{
       step('CompileJob') {
          build 'Compile Job'
       }
       step('Test') {
          build 'Test'
       }
       step('Deploy') {
          build 'Deploy'
       }
    }
}
