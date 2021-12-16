Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "hello World"'
                sh '''
                    echo "Multilne shell steps works too"
                    ls -lah
                ...
            }
        }
    }
}