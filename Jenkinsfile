@Library('Jenkins_lib') _

pipeline{
    agent any

    stages{

        stage("Git chcekout") {
            steps{
                gitCheckout(
                    branch: 'main', 
                    url: 'https://github.com/GauravJ1128/Java-application.git'
                )
            }
        }

        stage("maven test"){
            steps{
                script{
                    mvnTest()
                }
            }
        }

    }
}