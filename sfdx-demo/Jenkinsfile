pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script {
                    echo 'Hello World'
                    bat ''' git --version '''
            
                }
            }
        }
    }
}
