@Library('jenkins-shared-library@main') _
pipeline{
    agent any
    stages{
        stage('Greeting'){
            steps{
                greetUser('Learner')
            }
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
