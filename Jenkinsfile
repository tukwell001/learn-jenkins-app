pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'echo " Hello from jenkins"'
                sh "whoami"
                sh "java --version"
            }
        }
    }
}
