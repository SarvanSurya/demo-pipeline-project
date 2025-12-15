@Library('jenkins-shared-library') _
pipeline{
    agent any
    stages{
        stage('Greeting'){
            greetUser('Learner')
        }
        stage('Build Info'){
            steps{
                script{
                    org.example.Util.printBuildInfo(this)
                }
            }
        }
    }





}
