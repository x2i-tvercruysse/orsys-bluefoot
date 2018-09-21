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
                    echo "Tests on Linux"
                },
                b: {
                    echo "Tests on Windows"
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
