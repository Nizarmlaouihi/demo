pipeline {
    agent any
    options {
      skipDefaultCheckout false
    }

    stages {      
        stage('hello') {
            steps {
               sh 'cat test.txt'
            }
        }
    }
}
