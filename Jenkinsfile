def modules = [:]
pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                script{
                    modules.first = load "first.groovy"
                    modules.first.test1()
                }
            }
        }
    }
}
