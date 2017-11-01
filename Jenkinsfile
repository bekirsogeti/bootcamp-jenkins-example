#!groovy

pipeline{

    agent any

    steps{
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
