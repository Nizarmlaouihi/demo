pipeline {
    agent any
    options {
      skipDefaultCheckout true
    }

    stages {      
        stage('hello') {
            steps {
               sh 'cat demo.txt'
            }
        }
    }
}
