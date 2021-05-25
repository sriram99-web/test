pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Hello World"'
                bat '''
                    echo "Hello World"
                    echo "Multiline shell steps works too"
                '''
            }
        }
    }
}
