@Library('Jenkins_lib')



pipeline {
    agent any

    stages {

        stage("Git chcekout") {
            steps {
                script{
                    git branch: 'main', 
                    url: 'https://github.com/GauravJ1128/Java-application.git'
                }
            }
        }
    }
}