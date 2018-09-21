pipeline {
    agent none
    stages {
        stage('Run Tests') {
            parallel {
                stage('Test On node1') {
                    agent { label "test1" }
                    steps {
                        echo "run-tests1.sh"
                    }
                }
                stage('Test On node2') {
                    agent { label "test2" }
                    steps {
                        echo "run-tests2.sh"
                    }
                }
            }
        }
    }
}
