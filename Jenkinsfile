pipeline {
    agent none
    stages {
        stage('Run Tests') {
            parallel {
                stage('Test On node1') {
                    agent { label "test1" }
                    steps {
                        sh "run-tests.bat"
                    }
                }
                stage('Test On node2') {
                    agent { label "test2" }
                    steps {
                        sh "run-tests.sh"
                    }
                }
            }
        }
    }
}
