pipeline {
    
    agent any
    
    stages {
    
        stage('Build') {
           steps {
             sh 'echo "TODO"'
           }
        }
        
         stage('Test') {
           steps {
             parallel(
                a: {
                    echo "Tests A"
                },
                b: {
                    echo "Tests B"
                }
           }
        }
        
         stage('Deploy') {
           steps {
             sh 'echo "TODO"'
           }
        }
    
    }
}
